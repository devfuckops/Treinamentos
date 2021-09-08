

# **Helm**

Helm ajuda a gerenciar aplicativos Kubernetes - Helm Charts ajuda a definir, instalar e atualizar até mesmo o aplicativo Kubernetes mais complexo.

![Helm-icon | Brands HA - HZ](./imagens/34_helm-icon.2aa753566a.png)



O **Helm** é o gerenciador de pacotes do Kubernetes. Os pacotes gerenciados pelo Helm, são chamados de **charts**, que basicamente são formados por um conjunto de manifestos Kubernetes no formato YAML e alguns templates que ajudam a manter variáveis dinâmicas de acordo com o ambiente. O Helm ajuda você a definir, instalar e atualizar até o aplicativo Kubernetes mais complexo.

Os Helm charts são fáceis de criar, versionar, compartilhar e publicar.

O Helm é um projeto graduado no CNCF e é mantido pela comunidade, assim como o Kubernetes.

# **Treinamentos**

Colocar ✔ quando concluído. 

## Linux Tips

- Descomplicando Kubernetes - Helm
- https://github.com/devfuckops/DescomplicandoHelm
- https://github.com/devfuckops/DescomplicandoKubernetes/blob/main/day-4/DescomplicandoKubernetes-Day4.md#helm

## 

# **Documentação**



## **Instalando Helm**

https://helm.sh/docs/intro/install/



## **Charts**

https://artifacthub.io/

https://helm.sh/docs/topics/charts/

### The Chart File Structure

https://helm.sh/docs/topics/charts/#the-chart-file-structure

Estrutura do Chart

```yaml
wordpress/
  Chart.yaml          # A YAML file containing information about the chart
  LICENSE             # OPTIONAL: A plain text file containing the license for the chart
  README.md           # OPTIONAL: A human-readable README file
  values.yaml         # The default configuration values for this chart
  values.schema.json  # OPTIONAL: A JSON Schema for imposing a structure on the values.yaml file
  charts/             # A directory containing any charts upon which this chart depends.
  crds/               # Custom Resource Definitions
  templates/          # A directory of templates that, when combined with values,
                      # will generate valid Kubernetes manifest files.
  templates/NOTES.txt # OPTIONAL: A plain text file containing short usage notes
```



### The Chart.yaml File

https://helm.sh/docs/topics/charts/#the-chartyaml-file

```yaml
apiVersion: The chart API version (required)
name: The name of the chart (required)
version: A SemVer 2 version (required)
kubeVersion: A SemVer range of compatible Kubernetes versions (optional)
description: A single-sentence description of this project (optional)
type: The type of the chart (optional)
keywords:
  - A list of keywords about this project (optional)
home: The URL of this projects home page (optional)
sources:
  - A list of URLs to source code for this project (optional)
dependencies: # A list of the chart requirements (optional)
  - name: The name of the chart (nginx)
    version: The version of the chart ("1.2.3")
    repository: (optional) The repository URL ("https://example.com/charts") or alias ("@repo-name")
    condition: (optional) A yaml path that resolves to a boolean, used for enabling/disabling charts (e.g. subchart1.enabled )
    tags: # (optional)
      - Tags can be used to group charts for enabling/disabling together
    import-values: # (optional)
      - ImportValues holds the mapping of source values to parent key to be imported. Each item can be a string or pair of child/parent sublist items.
    alias: (optional) Alias to be used for the chart. Useful when you have to add the same chart multiple times
maintainers: # (optional)
  - name: The maintainers name (required for each maintainer)
    email: The maintainers email (optional for each maintainer)
    url: A URL for the maintainer (optional for each maintainer)
icon: A URL to an SVG or PNG image to be used as an icon (optional).
appVersion: The version of the app that this contains (optional). Needn't be SemVer. Quotes recommended.
deprecated: Whether this chart is deprecated (optional, boolean)
annotations:
  example: A list of annotations keyed by name (optional).
```



# **Links Úteis**

**Site Oficial**

https://helm.sh/







**Helm — O que é, e porque você deve usá-lo**

https://medium.com/@maths.nunes/o-que-%C3%A9-o-helm-e-porque-voc%C3%AA-deve-us%C3%A1-lo-508b7350dcd


