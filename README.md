# ¿Quién paga hoy? v1.10.0 #

### Versión inicial de la app que resuelve los problemas a la hora de decidir quién paga el desayuno conjunto de la oficina. ###

**Estructura:**
* _Landing page_ con el resumen de la situación actual. Permite añadir nuevos participantes habituales, consultar el perfil de cada usuario habitual, y el histórico de pagos.
<img width="350" height="698" alt="image" src="https://github.com/user-attachments/assets/fba5ec05-1e5b-423c-9116-364b95aacf0d" />



* _Desayuno de hoy_, que permite introducir el total de desayunos y quiénes de los habituales asisten. Admite más desayunos que habituales, por si acude algún invitado ocasional.
<img width="351" height="692" alt="image" src="https://github.com/user-attachments/assets/fe98720f-db56-4f7b-98a7-b7ba6f59ffbb" />



* _Le toca pagar a_, que decide quién debe pagar basándose en el total de desayunos pagados hasta la fecha. La primera vez que acude un habitual, le toca a otro. En caso de igualdad de condiciones, se elige por orden alfabético. Se permite elegir a otro comensal distinto del seleccionado, así como permitir que pague un invitado (en este caso, no se actualiza el total de desayunos consumidos por los habituales)
<img width="350" height="700" alt="image" src="https://github.com/user-attachments/assets/3e4af623-9c88-40cd-8e14-ebdff7db07f6" />



