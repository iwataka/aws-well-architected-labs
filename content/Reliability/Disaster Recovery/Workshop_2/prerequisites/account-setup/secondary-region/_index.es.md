+++
title = "Región secundaria"
date =  2021-05-11T11:43:28-04:00
weight = 3
+++

## Desplegando la plantila the Amazon CloudFormation

1.1 Cree la aplicación en la región secundaria **N. California (us-west-1)** lanzando una [Plantilla de CloudFormation](https://console.aws.amazon.com/cloudformation/home?region=us-west-1#/stacks/create/template?stackName=Pilot-Secondary&templateURL=https://ee-assets-prod-us-east-1.s3.amazonaws.com/modules/630039b9022d4b46bb6cbad2e3899733/v1/PilotLightDR.yaml).

1.2  Especifíque los detalles de la pila.

Cambie el parámetro **IsPrimary** al valor de `no`.

{{% notice info %}}
**Deje IsPromote and LatestAmiId con sus valores predeterminados**
{{% /notice %}}

1.3 Oprima el botón **Siguiente** para continuar.

{{< img sr-4-ES.png >}}

1.4 Deje los valores predeterminados en la página **Configurar opciones de pila** y oprima **Siguiente**.

1.5 Desplacese al fondo de la página y oprima la **casilla de verificación** para confirmar el entendimiento de que se crearán recursos de IAM, después oprima **Crear stack**.

{{< img sr-5-ES.png >}}

{{% notice info %}}
**Espere que termine la creación de la pila**.
{{% /notice %}}

{{< img sr-6-ES.png >}}

{{< prev_next_button link_prev_url="../primary-region/" link_next_url="../../../verify-primary-website/" button_next_text="Siguiente paso" button_prev_text="Paso anterior"/>}}