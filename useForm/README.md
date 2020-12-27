# useForm

```
const initialForm = {
    name: '',
    age: 0,
    email: ''
}
const [ formValues, handleInputChange, reset ] = useForm(initialForm);
```

// el useForm recibe el estado del formulario inicial y retorna los nuevos valores, una función para manejar los cambios de input, y un reset