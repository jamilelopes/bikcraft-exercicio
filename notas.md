min-width = acima de/maior que
max-width = abaixo de/menor que
} para @media
( ex: 'display grid /grid-template-columns'
@media (max-width: 500px)
Abaixo de 500px

@media (min-width: 600px)
Acima de 600px

@media (min-width: 800px) and (max-width: 900px)
Entre 800px e 900px.)

auto-fit - minmax } para display: grid.
.minmax {
grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
}
grid-template-columns: repeat(auto-fit, 150px);
}
