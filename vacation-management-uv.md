<center>

![](assets\univalle-rojopuro-159x226.jpg)

## APLICACIÓN WEB PARA LA GESTIÓN DE VACACIONES DE FUNCIONARIOS DE LA UNIVERSIDAD DEL VALLE

### BRYAN STEVEN BIOJÓ ROMERO

### 201629366

#### bryan.biojo@correounivalle.edu.co

## Director:

### OSCAR FERNANDO BEDOYA LEYVA, Ph.D.

#### oscar.bedoya@correounivalle.edu.co

#### Facultad de Ingeniería

#### Escuela de Ingeniería de Sistemas y Computación

#### Programa Académico de Ingeniería de Sistemas

#### Cali, Noviembre 21 de 2023

</center><br>

<center>

## Tabla de contenido

</center>

- Listado de Tablas

- Listado de Figuras

- Resumen

1. Planteamiento y Formulación del Problema

2. Justificación del Problema

   - 2.1. Justificación Académica.
   - 2.2. Justificación Económica.
   - 2.3. Justificación Social.

3. Objetivos

   - 3.1. Objetivo General.
   - 3.2. Objetivos Específicos.
   - 3.3. Resultados Esperados.

4. Alcances de la Propuesta

5. Marco Referencial

   - 5.1. Glosario.

   - 5.2. Estado del Arte.

   - 5.3. Marco Teórico.

6. Metodología

7. Presupuesto

8. Bibliografía

<center><br>

## Listado de tablas

</center>

- Tabla 1. Resultados esperados por objetivos específicos.

<center>

## Listado de figuras

</center>

- Figura 1.

<center>

## Resumen

</center>

<p style="text-align: justify;">
La tecnología ha sido un pilar fundamental en la evolución, permitiendo una mayor eficiencia, calidad y mejora constante de los procesos en diversas áreas, lo que a su vez ha impactado en nuestra calidad de vida. Tareas que eran repetitivas, lentas o complejas se han reducido o automatizado, lo que nos ha permitido enfocarnos en aspectos más relevantes.
</p>

<p style="text-align: justify;">
Sin embargo, muchas compañías e instituciones todavía realizan numerosas tareas manuales, las cuales consumen tiempo y son propensas a errores. En el caso de las universidades públicas y en particular en la Universidad del Valle (Colombia) esto se puede observar en diversos procesos como, por ejemplo, el cálculo de los periodos de vacaciones de los funcionarios. Este proceso es de vital importancia y requiere atención ya que deben tenerse en cuenta aspectos como: cuándo se pueden solicitar las vacaciones, cuántos días pueden tomar los funcionarios de acuerdo a su régimen, verificar el correcto diligenciamiento de los formatos de solicitud y reintegro, entre otras etapas.
</p>

<p style="text-align: justify;">
Este trabajo de grado se centra en el desarrollo de una aplicación web que apoye a los funcionarios de la Universidad del Valle en el proceso de gestión de vacaciones (solicitudes y reintegros) con el fin de que sea más rápido y se minimicen posibles errores debido a la intervención humana. Para lograr esto, es necesario identificar cada una de las etapas que se llevan a cabo para tramitar estas solicitudes, así como sus respectivas condiciones y/o restricciones.
</p><br>

## 1. Planteamiento y Formulación del Problema

<p style="text-align: justify;">
Actualmente una parte crucial del proceso de gestión de vacaciones de los funcionarios de la Universidad del Valle es el cálculo manual de las fechas de salida y reintegro. Este proceso es llevado a cabo individualmente por parte de los propios funcionarios.
</p>

<p style="text-align: justify;">
En general, el proceso de solicitud de vacaciones es el siguiente:
</p>

- El funcionario debe calcular manualmente el periodo de vacaciones seleccionado teniendo en cuenta su régimen, el cual determina el número de días a los que tiene derecho según la ley que rige a las universidades públicas colombianas.
- Una vez realizado el cálculo, el funcionario debe diligenciar y firmar una solicitud indicando la fecha de inicio de las vacaciones, el periodo al que corresponden y si se tomarán durante el periodo individual o colectivo. Si las vacaciones se quieren tomar de forma colectiva y el funcionario no ha cumplido con los plazos establecidos para solicitarlas, debe diligenciar un formato adicional.
- A continuación, el funcionario envía la solicitud al director(a) de la unidad académica o administrativa o a su jefe inmediato para su validación y revisión.
- El director(a) o jefe inmediato remite la información a la facultad, instituto o dependencia para su revisión y posterior envío al área de RRHH (Recursos Humanos).
- RRHH verifica nuevamente la solicitud y determina si el funcionario cumple con los requisitos. Si cumple, se inicia el trámite administrativo para el pago de las vacaciones y se notifica al funcionario la aprobación de su solicitud. En caso contrario, se notifica al director(a) de la unidad académica o administrativa o al jefe inmediato la razón por la cual no se aprueba la solicitud y después este(a) se lo comunica al funcionario.

<p style="text-align: justify;">
En cuanto al reintegro a las labores, el proceso es el siguiente:
</p>

- El funcionario debe completar y firmar un formato denominado P4, indicando si el motivo del reintegro es por finalización del periodo de vacaciones o anticipado debido a necesidad del servicio. En caso de un reintegro anticipado, debe registrar los días pendientes para que se puedan conceder posteriormente.
- A continuación, la solicitud pasa por el mismo trámite descrito en la solicitud de vacaciones a partir del tercer punto.

<p style="text-align: justify;">
Como se puede observar, el problema radica en que si el funcionario no realiza correctamente el cálculo del período de vacaciones, la solicitud será rechazada. Además, resulta laborioso conocer los días pendientes de vacaciones de un funcionario y el estado de las solicitudes de vacaciones o reintegros, ya que todo el proceso se realiza de forma manual.
</p>

<p style="text-align: justify;">
Por lo tanto, la pregunta de investigación que orienta este trabajo de grado es: ¿Es posible desarrollar una aplicación web que permita determinar el estado actual de las vacaciones de cada funcionario, controlar fechas calendario, automatizar el cálculo de estas fechas teniendo en cuenta todas las restricciones y registrar la aceptación o rechazo de las solicitudes.
</p><br>

## 2. Justificación del Problema

### 2.1. Justificación Académica

<p style="text-align: justify;">
Este trabajo de grado busca ampliar los conocimientos adquiridos en asignaturas como: Desarrollo de Software, Bases de Datos y Aplicaciones en la WEB y Redes Inalámbricas para desarrollar una aplicación web que agilice el proceso de gestión de vacaciones de los funcionarios de la Universidad del Valle. Además, este trabajo proporcionará una experiencia de aprendizaje en desarrollo web, abarcando aspectos de usabilidad, seguridad, calidad, entre otros.
</p>

### 2.2. Justificación Económica

<p style="text-align: justify;">
El proceso actual de gestión de vacaciones conlleva costos significativos y un gasto considerable en papelería. Además, se enfrenta al problema de solicitudes rechazadas, lo que implica la devolución de documentos y la repetición del proceso. Los errores en el cálculo de vacaciones pueden tener un impacto económico directo en los salarios de los funcionarios, resultando en pagos incorrectos. La implementación de una aplicación web para agilizar y automatizar este proceso permitiría un registro, control y seguimiento más eficientes, reduciendo los costos asociados a este proceso.
</p>

### 2.3. Justificación Social

<p style="text-align: justify;">
Este trabajo de grado impacta positivamente a la Universidad del Valle y puede servir como referencia para optimizar procesos similares dentro de esta o en otras instituciones. La automatización agiliza el acceso a información, fomentando la transparencia y equidad en la gestión. Además, mejora la eficiencia y efectividad en la toma de decisiones.
</p><br>

## 3. Objetivos

### 3.1. Objetivo General

<p style="text-align: justify;">
Desarrollar una aplicación web que permita la gestión de vacaciones de los funcionarios de la Universidad del Valle.
</p>

### 3.2. Objetivo Específicos

<ul style="text-align: justify;">
<li>Realizar la especificación del proceso de gestión de vacaciones mediante diagramas de modelado de procesos de negocio (BPM).</li>
<li>Diseñar e implementar un módulo para el control de fechas calendario de los periodos de vacaciones.</li>
<li>Diseñar e implementar un módulo para determinar el estado de vacaciones de los funcionarios.</li>
<li>Diseñar e implementar un módulo para la solicitud de vacaciones.</li>
<li>Diseñar e implementar un módulo de reintegro de vacaciones.</li>
<li>Evaluar la efectividad de los módulos desarrollados contra las diferentes etapas del proceso de forma manual.</li>

### 3.3. Resultados Esperados

| Objetivos Específicos | Producto(s) Esperados                                                                                                                        |
| --------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo 1            | Diagramas de BPM que muestren de forma clara y visual el proceso de gestión de vacaciones.                                                   |
| Objetivo 2            | Código fuente del módulo de control de las fechas calendario de los periodos de vacaciones.                                                  |
| Objetivo 3            | Código fuente del módulo para la determinación del estado de vacaciones de los funcionarios.                                                 |
| Objetivo 4            | Código fuente del módulo para la solicitud de vacaciones de los funcionarios.                                                                |
| Objetivo 5            | Código fuente del módulo de reintegro de vacaciones de los funcionarios.                                                                     |
| Objetivo 6            | Comparación de los tiempos empleados por los funcionarios al realizar la solicitud tanto de forma manual como a través de la aplicación web. |

<center>

**Tabla 1.** Resultados esperados por objetivos específicos.

</center><br>

## 4. Alcances de la Propuesta

<p style="text-align: justify;">
Este proyecto de grado se limitará al desarrollo de la aplicación web que permita la gestión del proceso de vacaciones de los funcionarios de la Universidad del Valle. El prototipo se realizará utilizando datos sintéticos.
</p><br>

## 5. Marco Referencial

<p style="text-align: justify;">
Este proyecto de grado se limitará al desarrollo de la aplicación web que permita la gestión del proceso de vacaciones de los funcionarios de la Universidad del Valle. El prototipo se realizará utilizando datos sintéticos.
</p><br>

### 5.1. Glosario

<ul style="text-align: justify;">
<li> <strong>Aplicación web:</strong> Aplicación informática que se accede a través de un navegador web y que funciona en internet.
<li><strong>Automatización de procesos:</strong> Uso de tecnología para realizar tareas y actividades de forma automática sin intervención humana con el objetivo de aumentar la eficiencia y reducir errores en los procesos de una organización.
<li><strong>Director:</strong> Persona que ocupa una posición de liderazgo en una organización, empresa, institución o grupo. Su rol implica la toma de decisiones importantes, la supervisión de actividades y la dirección de equipos o departamentos.</li>
<li><strong>Facultad:</strong> En el contexto académico, división o departamento dentro de una universidad que se especializa en un campo específico de estudio.</li>
<li><strong>Formato P4:</strong> Formato utilizado para la solicitud y registro de vacaciones en algunas organizaciones.</li>
<li><strong>Funcionario:</strong> Persona que ocupa un cargo o posición en una organización, institución gubernamental o empresa y desempeña funciones y responsabilidades específicas en el cumplimiento de sus deberes. En el contexto universitario, los funcionarios pueden incluir tanto al personal académico (profesores, investigadores) como al personal administrativo (personal de apoyo, directivos, personal de recursos humanos, etc.).</li>
<li><strong>Módulo:</strong> Parte o componente de un sistema más grande o de un programa informático que cumple una función específica y generalmente se puede usar de manera independiente o en conjunto con otros módulos.</li>
<li><strong>Período de vacaciones:</strong> Tiempo en el cual un empleado tiene derecho a tomar un descanso remunerado del trabajo.</li>
<li><strong>Recursos humanos (RRHH):</strong> Departamento encargado de atraer, retener y desarrollar talento humano, así como garantizar que los empleados tengan un ambiente laboral adecuado y se cumplan las leyes laborales y regulaciones.</li>
<li><strong>Régimen:</strong> Conjunto de normas, reglas y políticas que regulan las condiciones laborales, derechos, deberes y beneficios de los empleados de una organización.</li>
<li><strong>Reintegro de vacaciones:</strong> Proceso en el cual un empleado retorna a sus actividades laborales después de haber disfrutado de un período de vacaciones.</li>
<li><strong>Solicitud de vacaciones:</strong> Petición formal de un empleado para obtener permiso o autorización para tomar vacaciones.</li>
<li><strong>Unidad académica:</strong> Entidad dentro de una institución educativa que agrupa y organiza programas académicos relacionados con un campo particular de estudio o disciplina.</li>
<li><strong>Unidad administrativa:</strong> Entidad dentro de una organización, institución o empresa que se encarga de llevar a cabo tareas y responsabilidades relacionadas con la gestión y administración de los recursos, procesos y funciones de la entidad en cuestión.</li>
<li><strong>Universidad:</strong> Institución de educación superior que ofrece programas de enseñanza, investigación y extensión académica.</li>
<li><strong>Vacaciones colectivas:</strong> Período de descanso otorgado a todos los empleados de una organización al mismo tiempo.</li>
<li><strong>Vacaciones individuales:</strong> Período de descanso otorgado a un empleado de manera individual, según su derecho y acuerdo laboral.</li>
</ul><br>

### 5.2. Estado del Arte

#### 5.2.1 Implementación de un sistema Web para Talento Humano en la Universidad Central de Ecuador

<p style="text-align: justify;">
La Dirección de Talento Humano de la Universidad Central del Ecuador (UCE) enfrentaba diversos desafíos en la gestión de solicitudes relacionadas con el personal administrativo, incluyendo vacaciones, licencias, permisos, y el registro de sanciones. Su sistema de gestión, desarrollado en la herramienta empresarial PowerBuilder, era obsoleto, ineficiente, y no se adecuaba a las necesidades actuales. Además, procesos como la autorización y seguimiento de solicitudes de vacaciones se llevaban a cabo manualmente, lo que requería una cantidad significativa de tiempo y esfuerzo, causaba demoras en el procesamiento de solicitudes, propiciaba errores en los cálculos de días, resultaba en la pérdida de información crucial y no permitía la visibilidad del estado de estas solicitudes.
</p>

<p style="text-align: justify;">
En el caso de las solicitudes de vacaciones, el empleado debía presentar un oficio a su supervisor, quien decidía si aprobar o no la solicitud. En caso de aprobación, esta se enviaba a la Dirección de Talento Humano y era registrada por el Analista encargado del proceso. Todos los registros se consolidaban en una hoja de Excel con aproximadamente 1000 registros, cada una con atributos como nombre, departamento, régimen, fecha de ingreso, número de permisos en días y horas, saldos de vacaciones pendientes, entre otros.
</p>

<center>

![](assets\figs\fig1_archivo-vacaciones.png)

**Figura 1.** Archivo de vacaciones. Tomado de [].

</center>

<p style="text-align: justify;">
Después de registrar la información en la hoja de Excel, se generaba un documento en Word que requería ser personalizado con los datos del empleado antes de imprimirlo y enviarlo al director(a) de la Dirección de Talento Humano para su firma. Posteriormente, el documento firmado se entregaba al interesado.
</p>

<center>

![](assets\figs\fig2_autorizacion-vacaciones-anuales.png)

**Figura 2.** Autorización de vacaciones anuales. Tomado de [].

</center>

<p style="text-align: justify;">
Para afrontar estos desafíos, se diseñó y puso en marcha un sistema web utilizando Java como lenguaje de programación, JavaServer Faces (JSF) e Hibernate como frameworks, Wildfly como servidor de aplicaciones y Oracle Express 11g como motor de bases de datos para asegurar que esta fuese robusta y escalable. En el proceso de desarrollo se aplicó la metodología eXtreme Programming (XP) con el objetivo de garantizar que el sistema se creara de acuerdo con las necesidades reales de la Dirección de Talento Humano.
</p>

<p style="text-align: justify;">
El desarrollo del sistema web se enfocó en validar los siguientes objetivos:
</p>

- Identificar las necesidades y requerimientos funcionales del sistema.
- Gestionar la concesión de vacaciones de forma automática.
- Gestionar el registro de permisos personales.
- Gestionar la emisión de licencias de forma automática.
- Gestionar el registro de sanciones.
- Generar informes y reportes.

<br><p style="text-align: justify;">
Con la implementación del módulo, se logró optimizar el tiempo en los diferentes procesos mencionados, permitiendo que las solicitudes de los funcionarios fuesen atendidas de forma rápida y eficiente.

</p>

<center>

![](assets\figs\fig3_prototipo-menu-principal.png)

**Figura 3.** Prototipo del menú principal. Tomado de [].

</center>

<center>

![](assets\figs\fig4_formulario_registro_vacaciones.png)

**Figura 4.** Formulario de registro de vacaciones. Tomado de [].

</center>

<center>

![](assets\figs\fig5_formato-autorizacion-vacaciones.png)

**Figura 5.** Formato de autorización de vacaciones autogenerado. Tomado de [].

</center>

<p style="text-align: justify;">
El proceso de solicitud de vacaciones se consolidó de la siguiente forma:
</p>

<center>

![](assets\figs\fig6_nuevo-registro-vacaciones.png)

**Figura 6.** Nuevo Registro de Vacaciones. Tomado de [].

</center>

<p style="text-align: justify;">
De todo el proceso de desarrollo del sistema web se obtuvieron las siguientes conclusiones:
</p><br>

- La aplicación web contribuyó en gran medida a establecer procesos específicos para la concesión de vacaciones y permisos que antes no estaban claramente definidos.
- La gestión automatizada de la concesión de vacaciones permitió mantener registros actualizados de los saldos de vacaciones, lo que agilizó la emisión de autorizaciones y garantizó respuestas rápidas a las solicitudes.
- La información administrativa relacionada con los empleados de la UCE pudo centralizarse en los servidores de la Dirección de Tecnología.
- Se logró segmentar la información de los empleados, evitando la carga masiva de datos, como ocurría en el sistema anterior de Talento Humano.

### 5.3. Marco Teórico

## 6. Metodología

### 6.1 Actividades a realizar

### 6.2 Cronograma de actividades

## 7.2 Presupuesto

### 7.1 Presupuesto total del proyecto

### 7.2 Presupuesto detallado del personal

### 7.3 Presupuesto detallado del hardware

## Bibliografía

-
