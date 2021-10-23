# K8s reference

Reference for k8s certification

## Preparation and rationale

#### Official resources

- [Portal](https://trainingportal.linuxfoundation.org/learn/dashboard) (acquired after booking)
- [Certification handbook](https://docs.linuxfoundation.org/tc-docs/certification/lf-candidate-handbook)
- [Important instructions](https://docs.linuxfoundation.org/tc-docs/certification/tips-cka-and-ckad)

#### Format

- 2 hours hands-on, solving "hard" problems
- A proctor watches you perform the exam live
- You can only access specific pages

#### Environment

- ubuntu 18:04, no extra packages
- `kubectl` and alias `k`
- `helm` (no `kubens`)
- `vim` (no config)

## Setup

Setup vim (for working with yaml)

```shell
alias vi=vim ; cat <<EOF >~/.vimrc
set number
set shiftwidth=2
autocmd FileType yaml setlocal ts=2 sts=2 sw=2 expandtab
EOF
```

## Cheatsheet

Allowed top-level pages during exam ([source](https://docs.linuxfoundation.org/tc-docs/certification/certification-resources-allowed#certified-kubernetes-administrator-cka-and-certified-kubernetes-application-developer-ckad)):

- https://kubernetes.io/docs/home/
- https://github.com/kubernetes/
- https://kubernetes.io/blog/

Relevant allowed sub-pages:

- [Change current namespace](https://kubernetes.io/docs/concepts/overview/working-with-objects/namespaces/#setting-the-namespace-preference)



