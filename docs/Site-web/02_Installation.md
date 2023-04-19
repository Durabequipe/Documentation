# Installation

## Cloner le projet

```bash
git clone https://github.com/Durabequipe/SiteWeb
```

## Installer les dépendences

```bash
npm install
```

## Configurer le projet

```bash
cp src/environments/environment.sample.ts src/environments/environment.ts
cp src/environments/environment.sample.ts src/environments/environment.prod.ts
```

## Remplir les variables d'environnement

```bash
# src/environments/environment.ts
apiUrl: "{{ url de l'administration }}/api/",
apiToken: "{{ la clé d'api }}",
```

## Lancer le projet

```bash
npm run start
```

## Compiler le projet

```bash
npm run build
```