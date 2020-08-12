 857  mkdir git-learn
  858  cd git-learn
  859  ls
  860  git init
  861  ls
  862  git remove -V
  863  git remote -v
  864  ls
  865  pwd
  866  touch index.js
  867  code index.js
  868  git status
  869* pwd
  870* ls
  871* cd projetos/git-learn
  872* ls
  873* git status
  874  git remote add origin https://github.com/jebnascimento/git-learning.git
  875  git remote --list
  876  git remote -v
  877  clear
  878  git config --system --edit
  879  clear
  880  git config --global --edit
  881  git config --global code.editor code
  882  git config --global --edit
  883  git config --global core.editor code
  884  git config --global --edit
  885  git config --system --edit
  886  git config --global --edit
  887  git config --edit
  888  ls
  889  git status
  890  git add index.js
  891  git status -s
  892  git statys
  893  git status
  894  git commit -m "add index.js"
  895  git config --global --edit
  896* clear
  897* npm init
  898* clear
  899  git config --global --edit
  900* git s
  901* npm init -y
  902* clear
  903* ls
  904* git c
  905* git c "add npm"
  906* git s
  907* clear
  908* cd config
  909* cd ..
  910* ls
  911* git s
  912* git c "add routes and config"
  913* git s
  914* git status
  915* git log
  916* git s
  917* clear
  918* ls
  919* git s
  920* clear
  921* git c "modify routes"
  922* npm -i express
  923* npm install express
  924* git s
  925* git add .gitignore
  926* git commit -m "add .gitignore"
  927* ls
  928* git s
  929* git c "add express"
  930* git s
  931* git add .
  932* git stash
  933* clear
  934* git stash apply
  935* git s
  936* git stash list
  937* clear
  938* git s
  939* git stash
  940* git stash list
  941* git stash apply
  942* git s
  943* git stash clear
  944* git stash list
  945* git stash
  946* git stash pop
  947* git stash list
  948* clear
  949* pwd
  950* git s
  951* git c "verify git stash feat"
  952* npm i git-commit-msg-linter -D
  953* clear
  954* git c "add commit linter"
  955* git c "chore: add commit linter"
  956* clear
  957* git log
  958* git log --pretty=format:'%h %d %s - %cn, %cr'
  959* clear
  960* git log --pretty=format:'%C(blue)%h %C(red)%d %C(white)%s - %C(cyan)%cn, %C(yellow)%cr'
  961  git l
  962  clear
  963* git tag 1.0 -m "release 1.0"
  964* git l
  965* git tag -a "0.1.beta release" -m "release 0.1.beta" 12f3183
  966* git tag -a "0.1.beta" -m "release 0.1.beta" 12f3183
  967* git l
  968* clear
  969* git push origin master --follow-tags
  970* clear
  971* git s
  972* git add .
  973* clear
  974* git reset teste.js
  975* git s
  976* git reset
  977* git s
  978* clear
  979* git c "feat: add teste.js"
  980* git s
  981* git l
  982* clear
  983* git l
  984* git config --global core.pager cat
  985* git l
   986* git reset a442996 --soft
  987* git l
  988* clear
  989* git status
  990* git s
  991* git c "fix: add test.js"
  992* git l
  993* git his
  994* history
  995* clear
  996* git l
  997* git s
  998* git reset HEAD~1 --mixed
  999* git s
 1000* git l
 1001* git c "fix: add test.js"
 1002* clear
 1003* git l
 1004* git reset HEAD~1 --hard
 1005* git l
 1006* git s
 1007* clear
 1008* git s
 1009* git reset
 1010* git s
 1011* git reset --hard
 1012* git l
 1013* git c "feat: add feature"
 1014* clear
 1015* git l
 1016* git revert e8500f0
 1017* git s
 1018* git c "fix: modify package.json"
 1019* git l
 1020* git revert --continue
 1021* git l
 1022* clear
 1023* git revert --continue
 1024  /    fgyth uki
 1025  ls
 1026  code .
 1027* git log
 1028* git l
 1029* clear
 1030* git l
 1031* git s
 1032* git revert aa20f96
 1033* git l
 1034* git c
 1035* git c "fix: remove index.js"
 1036* git revert --continue
 1037* clear
 1038* git l
 1039* git log --oneline
 1040* git c "fix: modify routes"
 1041* git c "feat: create port var"
 1042* git c "feat: add console log to main"
 1043* clear
 1044* git l
 1045* git revert HEAD
 1046* git l
 1047* git revert 6c85a23
 1048* clear
 1049* git l
 1050* git reset ea0e62c --hard
 1051* git l
 1052* clear
 1053* git revert HEAD~1 --no-edit
 1054* git l
 1055* git reset ea0e62c --hard
 1056* git l
 1057* clear
 1058* git revert HEAD~1 --no-commit
 1059* git s
 1060* git l
 1061* git c "fix: teste"
 1062* git s
 1063* git checkout routes/routes.js
 1064* git s
 1065* clear
 1066* git s
 1067* git add .
 1068* git s
 1069* clear
 1070* pwd
 1071* ls
 1072* git checkout routes/routes.js
 1073* git s
 1074* git reset
 1075* git s
 1076* clear
 1077* git checkout .
 1078* git s
 1079* git l
 1080* git s
 1081* git add .
 1082* git reset
 1083* git s
 1084* clear
 1085* git s
 1086* git add .
 1087* git s
 1088* git checkout .
 1089* git s
 1090* clear
 1091* ls
 1092* git reset
 1093* ls
 1094* git checkout .
 1095* clear
 1096* git s
 1097* git add .
 1098* clear
 1099* ls
 1100* git l
 1101* git checkout 12f3183
 1102* git s
 1103* git reset
 1104* clear
 1105* ks
 1106* git s
 1107* git rm .
 1108* clear
 1109* git rm routes/routes.js
 1110* git rm -f routes/routes.js
 1111* git reset HEAD
 1112* git s
 1113* git l
 1114* clear
 1115* git reset HEAD
 1116* git s
 1117* git stash
 1118* git reset --hard HEAD
 1119* git stash pop
 1120* git l
 1121* clear
 1122* git stash
 1123* git s
 1124* git stash clean
 1125* git stash list
 1126* git stash clear
 1127* clear
 1128* git stash list
 1129* git l
 1130* git checkout 6ace682
 1131* clear
 1132* git l
 1133* git branch
 1134* git checkout master
 1135* git checkout 6ace682
 1136* clear
 1137* git branch
 1138* git checkout -b fix/index
 1139* git branch
 1140* git s
 1141* git l
 1142* git c "fix: hello world"
 1143* clear
 1144* git s
 1145* git l
 1146* git branch
 1147* git checkout master
 1148* git branch
 1149* git merge fix/index
 1150* clear
 1151* git c "fix index"
 1152* git c "fix: index"
 1153* clear
 1154* git l
 1155* clear
 1156* git clean n
 1157* git clean -n
 1158* git clean
 1159* git clean -f
 1160* git s
 1161* clear
 1162* git s
 1163* git clean
 1164* git config --local clean.requireForce false
 1165* git config --edit
 1166* git s
 1167* git clean
 1168* clear
 1169* git stash
 1170* git l
 1171* clear
 1172* git branch
 1173* git rm teste.js
 1174* pwd
 1175* git s
 1176* git add teste.js
 1177* git rm teste.js
 1178* git rm -f teste.js
 1179* git s
 1180* clear
 1181* git s
 1182* git rm -r routes/
 1183* git s
 1184* git reset
 1185* git s
 1186* git checkout .
 1187* git rm -r routes/
 1188* git s
 1189* clear
 1190* git c "fix: remove routes"
 1191* git l
 1192* git
 1193* git s
 1194* git c "chore: add index.js in gitignore"
 1195* git s
 1196* git rm index.js --cached
 1197* git s
 1198* clear
 1199* git s
 1200* git status
 1201* git c "fix: index.js"
 1202* clear
 1203* git s
 1204  ls
 1205  cd ..
 1206  ls
 1207  cd git-learn
 1208  ls
 1209  git push origin master