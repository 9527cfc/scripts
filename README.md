带图形js命令
ql repo https://hub.hanada.ltd/a592345029/scripts.git "jd_|jx_|getJDCookie" "activity|backUp" "^jd[^_]|USER|JDJR|sign_"

安装依赖1


docker exec -it qinglong bash -c "apk add --no-cache build-base g++ cairo-dev pango-dev giflib-dev && cd scripts && npm install canvas --build-from-source"


安装依赖2
docker exec -it qinglong bash -c "cd scripts && npm i -S png-js"
