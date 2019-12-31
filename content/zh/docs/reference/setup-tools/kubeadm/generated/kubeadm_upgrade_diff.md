<!--
### Synopsis

Show what differences would be applied to existing static pod manifests. See also: kubeadm upgrade apply --dry-run
-->
### 概述

显示哪些差异将被应用于现有的静态 pod 资源清单。参考: kubeadm upgrade apply --dry-run

```
kubeadm upgrade diff [version] [flags]
```
<!--
### Options

```
<tr>
  <td colspan="2">--api-server-manifest string&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Default: "/etc/kubernetes/manifests/kube-apiserver.yaml"</td>
</tr>
<tr>
  <td></td><td style="line-height: 130%; word-wrap: break-word;">path to API server manifest</td>
</tr>

<tr>
  <td colspan="2">--config string</td>
</tr>
<tr>
  <td></td><td style="line-height: 130%; word-wrap: break-word;">Path to a kubeadm configuration file.</td>
</tr>

<tr>
  <td colspan="2">-c, --context-lines int&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Default: 3</td>
</tr>
<tr>
  <td></td><td style="line-height: 130%; word-wrap: break-word;">How many lines of context in the diff</td>
</tr>

<tr>
  <td colspan="2">--controller-manager-manifest string&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Default: "/etc/kubernetes/manifests/kube-controller-manager.yaml"</td>
</tr>
<tr>
  <td></td><td style="line-height: 130%; word-wrap: break-word;">path to controller manifest</td>
</tr>

<tr>
  <td colspan="2">-h, --help</td>
</tr>
<tr>
  <td></td><td style="line-height: 130%; word-wrap: break-word;">help for diff</td>
</tr>

<tr>
  <td colspan="2">--kubeconfig string&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Default: "/etc/kubernetes/admin.conf"</td>
</tr>
<tr>
  <td></td><td style="line-height: 130%; word-wrap: break-word;">The kubeconfig file to use when talking to the cluster. If the flag is not set, a set of standard locations can be searched for an existing kubeconfig file.</td>
</tr>

<tr>
  <td colspan="2">--scheduler-manifest string&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Default: "/etc/kubernetes/manifests/kube-scheduler.yaml"</td>
</tr>
<tr>
  <td></td><td style="line-height: 130%; word-wrap: break-word;">path to scheduler manifest</td>
</tr>
```

-->
### 选项

<tr>
  <td colspan="2">--api-server-manifest string&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;默认值： "/etc/kubernetes/manifests/kube-apiserver.yaml"</td>
</tr>
<tr>
  <td></td><td style="line-height: 130%; word-wrap: break-word;">API服务器清单的路径</td>
</tr>

<tr>
  <td colspan="2">--config string</td>
</tr>
<tr>
  <td></td><td style="line-height: 130%; word-wrap: break-word;"> API 服务器清单的路径。</td>
</tr>

<tr>
  <td colspan="2">-c, --context-lines int&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;默认值： 3</td>
</tr>
<tr>
  <td></td><td style="line-height: 130%; word-wrap: break-word;">差异中有多少行上下文</td>
</tr>

<tr>
  <td colspan="2">--controller-manager-manifest string&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;默认值： "/etc/kubernetes/manifests/kube-controller-manager.yaml"</td>
</tr>
<tr>
  <td></td><td style="line-height: 130%; word-wrap: break-word;">控制器清单的路径</td>
</tr>

<tr>
  <td colspan="2">-h, --help</td>
</tr>
<tr>
  <td></td><td style="line-height: 130%; word-wrap: break-word;">帮助</td>
</tr>

<tr>
  <td colspan="2">--kubeconfig string&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;默认值： "/etc/kubernetes/admin.conf"</td>
</tr>
<tr>
  <td></td><td style="line-height: 130%; word-wrap: break-word;">与集群通信时使用的 kubeconfig 文件，如果标志是未设置，则可以在一组标准位置中搜索现有的 kubeconfig 文件。</td>
</tr>

<tr>
  <td colspan="2">--scheduler-manifest string&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;默认值："/etc/kubernetes/manifests/kube-scheduler.yaml"</td>
</tr>
<tr>
  <td></td><td style="line-height: 130%; word-wrap: break-word;">调度程序清单的路径</td>
</tr>

<!--
### Options inherited from parent commands

```
<tr>
  <td colspan="2">--rootfs string</td>
</tr>
<tr>
  <td></td><td style="line-height: 130%; word-wrap: break-word;">[EXPERIMENTAL] The path to the 'real' host root filesystem.</td>
</tr>
```

-->
### 从父命令继承的选项


<tr>
  <td colspan="2">--rootfs string</td>
</tr>
<tr>
  <td></td><td style="line-height: 130%; word-wrap: break-word;">[EXPERIMENTAL] “真实”主机根文件系统的路径。</td>
</tr>

<!--
SEE ALSO
-->
参考
<!--
- [kubeadm upgrade](https://github.com/kubernetes/website/blob/release-1.16/content/en/docs/reference/setup-tools/kubeadm/generated/kubeadm_upgrade.md) - Upgrade your cluster smoothly to a newer version with this command
-->

- [kubeadm upgrade](https://github.com/kubernetes/website/blob/release-1.16/content/en/docs/reference/setup-tools/kubeadm/generated/kubeadm_upgrade.md) - 使用此命令将集群平滑升级到新版本