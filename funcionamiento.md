## Primer playbook
### Código:

```
---
- name: Playbook de Debug Simple
  hosts: all
  gather_facts: no

  tasks:
    - name: Mostrar mensaje simple
      debug:
        msg: "Hola, este es un mensaje de depuración en Ansible."

```

- Se define un playbook con - name: Playbook de Debug Simple.

- Se usa hosts: all, lo que significa que se ejecutará en todas las máquinas.

- gather_facts: no evita la recolección de información del sistema (para hacerlo más rápido).

- Se define una tarea con el módulo debug que muestra un mensaje.
