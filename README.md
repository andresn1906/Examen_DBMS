# Examen de Manejo de bases de datos

## Normalización:

### Primera forma de Normalización (1FN): 
- Cada tabla contiene atributos con valores únicos (atómico)
- Cada tabla contiene un atributo primario o clave que la caracteriza
- Esta forma de normalización se demuestra en cada tabla al darles atributos con un único valor y sin valores nulos o inexistentes. También, cada tabla contiene un atributo primario que no reincide.

### Segunda forma de Normalización (2FN): 
- Presente tras la 1FN
- Los atributos dependen parcialmente de los atributos primarios, es decir, los atributos de cada tabla no dependen totalmente del atributo primario

### Tercera forma de Normalización (2FN): 
- Presente tras la 1FN y 2FN
- Se presenta la separación de esquemas por cardinalidad al presentarse un problema de conflictos entre una relación N:M, por ende, se separan las dos tablas a través de una tabla intermedia y se evita la dependencia transitiva 
