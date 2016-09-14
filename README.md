# Document

## Git Command frequent
```
git add -A
git commit -m ""
git pull origin master
git push origin master --force
git branch -D feature/div.0.0.0.1
git status
del /F /S /Q /A .git
git push -f
npm install rimraf -g
rimraf node_modules
```

##Trianing onic : https://docs.google.com/document/d/13C1-N1KzUHzoSRVoBE39lyC5Q5CbevqRjvv9ZcQ9lfs/edit?usp=sharing

##Ctryral Report
```
dateVar d := CDate({DatabaseFields.ReportFields});
numberVar yyyy := Year(d);
    numberVar mm := Month(d);
    numberVar dd := Day(d);
    ToText(CDate(yyyy,mm,dd),"dd/MM/")+ToText(yyyy+543,0,"")
    
numberVar aa := 0;
select {ReportFields}
case "1" :  aa := {DatabaseFields.ReportFields}
case "2" :  aa := {DatabaseFields.ReportFields}
default: aa;
aa
```
