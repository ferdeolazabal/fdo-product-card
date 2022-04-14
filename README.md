# FDO-Product-card
### Fernando de Olazábal

Este es un paquete de pruebas de despliegue en NPM


## Ejemplo
```
import { ProductCard, ProductTitle, ProductImage, ProductButtons } from 'fdo-product-card'
```

```
<ProductCard 
    product={ product } 
    initialValues={{
        count: 4,
        // maxCount: 10
    }}
>
    {
        ( { reset, isMaxCountReached, count, product, increaseBy, maxCount } ) => (
            <>
                <ProductImage />
                <ProductTitle />
                <ProductButtons />
            </>
        )
    }
    
</ProductCard>
```

