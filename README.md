# Steps to Generate a Base Project With RESTEasy

### #1 Download or clone the project
`$ git clone https://github.com/svitorroberto/vitor-archetype`

### #2 Then move to that downloaded directory and call `mvn install` on the base archetype
```
$ cd vitor-archetype/
$ mvn install
```

### #3 Finally move to a fresh directory and use your archetype
```
$ mkdir /tmp/archetype
$ cd /tmp/archetype
$ mvn archetype:generate -DarchetypeCatalog=local
Choose a number or apply filter (format: [groupId:]artifactId, case sensitive contains): 1: 1
```

### #4 Adapt to your necessity
Done!

