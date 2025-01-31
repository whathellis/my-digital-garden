`dataviewjs
for (let group of dv.pages('"06 Plan/05"').groupBy(p => p.file.folder)) {
	dv.table(["Goal", "Deadline", "Date", "🧠"],
		group.rows
			.sort(k => k.date, 'desc')
			.map(c => [c.file.link, c.deadline, c.date, c.file.outlinks]))
}
`