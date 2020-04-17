## to update readme:

- delete existing README
- go to `/images` directory
- run `ls | awk '{ printf "![%s](/images/%s)\n", $1, $1 }' >> ../README.md`
