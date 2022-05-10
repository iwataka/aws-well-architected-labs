+++
title = "Región secundaria"
date =  2021-05-11T11:43:28-04:00
weight = 3
+++

### Desplegando la plantilla de Amazon CloudFormation

1.1 Cree la aplicación en la región secundaria **N. California (us-west-1)** lanzando esta [Plantilla de CloudFormation](https://console.aws.amazon.com/cloudformation/home?region=us-west-1#/stacks/create/template?stackName=Passive-Secondary&templateURL=https://ee-assets-prod-us-east-1.s3.amazonaws.com/modules/630039b9022d4b46bb6cbad2e3899733/v1/HotStandby.yaml).

1.2  Especifique los parámetros de la pila.

Cambie el valor del parámetro **IsPrimary** a `no`.

{{% notice info %}}
**Deje los valores predeterminados para LatestAmiId**
{{% /notice %}}

1.3 Oprima **Siguiente** para continuar.

{{< img sr-4-es.png >}}

1..4 Deje los valores predeterminados en la página **Configurar opciones de pila** y oprima **Siguiente** para continuar.

1.5 Desplacedse al fondo de la página y oprima la **casilla de verificación** para aceptar la creación de roles IAM, posteriormente oprima **Crear pila**.

{{< img sr-5-es.png >}}

{{< prev_next_button link_prev_url="../primary-region/" link_next_url="../../cfn-outputs/" button_next_text="Siguiente paso" button_prev_text="Paso anterior"/>}}