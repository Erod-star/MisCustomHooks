# useForm Hook


Ejemplo de uso:

```
    const initialForm = {
        name: '',
        age: 0,
        email,
    };

    const [ formValues, handleInputChange, reset ] = useForm(initalForm);   
```

useCounter() // Recibe un valor por defecto