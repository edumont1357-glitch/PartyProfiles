**### Particule 2
q2=+e      # Charge électrique
x2=1       # Abscisse en m
y2=0       # Ordonnée en m

### Distance particule 2-point (x,y)
r2=((x-x2)**2+(y-y2)**2)**0.5

### Coordonnée radiale champ E2
E2=K*q2/r2**2

### Coordonnées vecteur unitaire 2
ux2=(x-x2)/r2
uy2=(y-y2)/r2

### Coordonnées cartésiennes champ E2
Ex2=E2*ux2
Ey2=E2*uy2
**
