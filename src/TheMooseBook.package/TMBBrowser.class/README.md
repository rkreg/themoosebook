root := './iceberg-cache/girba/themoosebook/book' asFileReference.
TMBBrowser new openOn: 
	(root files select: [ :each | each extension = 'pillar' ]), 
	((root / 'Chapters') allFiles select: [ :each | each extension = 'pillar' ])