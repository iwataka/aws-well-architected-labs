+++
title = "Verificar failover"
date =  2021-05-11T11:43:28-04:00
weight = 6
+++

## Región secundaria

1.1 Navegue a [Pilas de CloudFormation](https://console.aws.amazon.com/cloudformation/home?region=us-west-1#/stacks/) en la región **N. California (us-west-1)**.

1.2 Escoja la pila **Warm-Secondary**.

1.3 Navegue a la pestaña **Salidas**.

{{< img vw-6-es.png >}}

1.4 Oprima el link de salida **WebsiteURL**.

## Verifique la página web

2.1 Inicie sesión en la aplicación. Tendrá que usar el email registrado en la sección **Pre-requisitos > Región primaria**.

2.2 Debería ver los elementos en su carrito de compras que añadió en la región primaria **N. Virginia (us-east-1)**.

{{< img vf-1.png >}}

{{< prev_next_button link_prev_url="../failover/promote-aurora/" link_next_url="../cleanup" button_next_text="Siguiente paso" button_prev_text="Paso anterior"/>}}

