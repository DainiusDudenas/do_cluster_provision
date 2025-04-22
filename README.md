savo WSL paleidau
Sita gavau is githubo, pasidariau per https://github.com/settings/personal-access-tokens
export GITHUB_TOKEN=github_pat_11A...Aa9kV3TZP57CEBW8rmuSlJq

flux bootstrap github --token-auth --owner=dainiusdudenas --repository=do_cluster_provision --branch=main --path=clusters/staging --personal --kubeconfig /home/tenant/do-provision-k8s-tf/fra1-single-node-kubeconfig.yaml
