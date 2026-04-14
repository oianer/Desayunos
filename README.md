# ¿Quién paga hoy? v1.10.0 #

### Versión inicial de la app que resuelve los problemas a la hora de decidir quién paga el desayuno conjunto de la oficina. ###

**Estructura:**
* _Landing page_ con el resumen de la situación actual. Permite añadir nuevos participantes habituales, consultar el perfil de cada usuario habitual, y el histórico de pagos.
<img width="350" height="731" alt="image" src="https://github.com/user-attachments/assets/4a801112-6df0-47f8-b0f3-ac5b04df390f" />


* _Desayuno de hoy_, que permite introducir el total de desayunos y quiénes de los habituales asisten. Admite más desayunos que habituales, por si acude algún invitado ocasional.
<img width="352" height="782" alt="image" src="https://github.com/user-attachments/assets/877c64ce-9ada-47f6-83b0-29be3e564200" />


* _Le toca pagar a_, que decide quién debe pagar basándose en el total de desayunos pagados hasta la fecha. La primera vez que acude un habitual, le toca a otro. En caso de igualdad de condiciones, se elige por orden alfabético. Se permite elegir a otro comensal distinto del seleccionado, así como permitir que pague un invitado (en este caso, no se actualiza el total de desayunos consumidos por los habituales)
<img width="346" height="780" alt="image" src="https://github.com/user-attachments/assets/349abe30-20f7-487a-8f70-64b540eae845" />


