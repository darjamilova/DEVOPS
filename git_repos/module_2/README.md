# 13. Salīdzināt vienādu failu (ne README) hash no mapes module_1 un module_2. Vai git redz atšķirību starp šiem failiem?
.png failu hash ir vienāds abās mapēs. Git neredz atškirību starp šiem failiem.

# Commits last week:
```sh
git log --all --since=1.weeks
git log --all --since="last week"
```

# Laura Pacilio commits:
```sh
git log --all --author="Laura Pacilio"
```

# Laura Pacilio commits on 09.2021
```sh
git log --all --after="01.09.2021 00:00" --before="30.09.2021 23:59" --author="Laura Pacilio"
```

# Laura Pacilio commits yesterday
```sh
git log --all --since=yesterday.midnight --author="Laura Pacilio"
```

