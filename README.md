# INVERSOR 100

Dashboard educativo de investigación de inversiones para un capital inicial desde **100 USD**, perfil moderado, horizonte de 3 a 5 años y acceso desde México y Colombia.

## Funciones
- Ranking editorial inicial de 10 ETFs y acciones con puntuación y nivel de riesgo.
- Enlaces para consultar cotizaciones externas. **No se presentan cotizaciones ficticias ni se afirma disponer de datos en tiempo real.**
- Simulador de aportaciones y rentabilidad hipotética.
- Propuesta de cartera ilustrativa y comprobaciones de seguridad.
- Funciona como sitio estático, sin dependencias ni claves API.

## Publicar con GitHub Pages
1. Abre **Settings → Pages** en el repositorio.
2. En **Build and deployment**, elige **Deploy from a branch**.
3. Selecciona **main** y **/(root)**, luego **Save**.
4. Cuando GitHub termine de publicar, abre https://otonielcruzmiguel-ux.github.io/inversor-100/ .

## Próximas mejoras
Para mostrar precios verificables automáticamente se necesitará integrar una API con permisos y límites adecuados. No incrustes claves privadas en JavaScript público ni en GitHub Pages. Para refrescos seguros, usa un backend o un workflow con secretos que genere un JSON público de precios con fuente y marca temporal.

> Información educativa; no constituye asesoría financiera o fiscal.
