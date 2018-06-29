This is a signed Readme


```
$ gpg --list-keys damian@strataconsulting.com
pub   rsa4096 2018-06-28 [SC] [expires: 2020-06-27]
      6DB9111B0BCEEA43A585A244712C45807C123618
uid           Damian Gitto Olguin <damian@strataconsulting.com>
uid           [jpeg image of size 7831]
sub   rsa4096 2018-06-28 [E] [expires: 2020-06-27]
sub   rsa4096 2018-06-28 [S] [expires: 2020-06-27]
```

signing a commit with GPG

```
$ git commit -S -m 'signed commit'
[master (root-commit) 71c683a] signed commit
 1 file changed, 2 insertions(+)
 create mode 100644 README.md
```
