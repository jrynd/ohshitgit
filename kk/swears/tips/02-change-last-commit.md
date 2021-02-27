---
tags: tip
title: Білә, мен коммит жасадым, кейін бір затты ұмытып кеткенім есіме түсті!
id: соңғы-коммитті-өзгерту
order: 2
---

```git
# өз өзгерісіңізді енгізіңіз
git add . # немесе жеке-жеке файлдарды қосыңыз
git commit --amend --no-edit
# енді осы өзгеріс сіздің соңғы коммитіңіздің ішінде
# ЕСКЕРТУ: жарияланған коммиттерді ешқашан өзгертпеңіз!
```

Егер мен коммит жасасам, содан кейін тесттер, линтерлар қоссам осындай бәле шығады. Біляяя тең белгісінің алдына пробел қоюды ұмытып кеттім. Жаңа өзгерісті енгізудің басқа да әдісі бар. Жаңа коммит жасаңыз, содан кейін `rebase -i` теріңіз. Сонда екі коммит қосылады. Бірақ бірінші әдіс тезірек.

*ЕСКЕРТУ: Ортақ тармаққа кеткен коммиттарды ешқашан өзгертпеңіз! Тек локал тармақтағы коммиттерді өзгертіңіз, немесе таяқ жейсіз.*