# pipelineNISTGitlab
# 🔒 Sécurité dans GitLab CI/CD

GitLab propose plusieurs outils de sécurité pour analyser votre code, vos dépendances et votre infrastructure. Voici un aperçu des principales fonctionnalités :

## 🛠️ **Analyse du Code**
| Fonctionnalité | Statut | Description |
|--------------|--------|-------------|
| **SAST (Static Application Security Testing)** | ❌ Non activé | Analyse statique du code source pour détecter des vulnérabilités. |
| **Advanced SAST** | 🔒 Ultimate requis | Analyse avancée du code avec des règles supplémentaires. |

## 🏗️ **Sécurité Infrastructure et Dépendances**
| Fonctionnalité | Statut | Description |
|--------------|--------|-------------|
| **Infrastructure as Code (IaC) Scanning** | ❌ Non activé | Analyse des fichiers de configuration Terraform, Kubernetes, etc. |
| **Dependency Scanning** | 🔒 Ultimate requis | Recherche des vulnérabilités connues dans les dépendances du projet. |

## 🌐 **Sécurité des Applications Déployées**
| Fonctionnalité | Statut | Description |
|--------------|--------|-------------|
| **DAST (Dynamic Application Security Testing)** | 🔒 Ultimate requis | Simule des attaques externes sur une application en cours d’exécution. |
| **DAST Profiles** | ✅ Activé | Gestion des profils pour les scans DAST. |
| **Container Scanning** | ❌ Non activé | Vérification des vulnérabilités dans les images Docker. |

## 🔍 **Autres Tests de Sécurité**
| Fonctionnalité | Statut | Description |
|--------------|--------|-------------|
| **Pipeline Secret Detection** | ❌ Non activé | Recherche automatique de secrets (clés API, tokens, etc.). |
| **Coverage Fuzzing** | 🔒 Ultimate requis | Exécute des tests de fuzzing pour détecter des failles potentielles. |
| **API Fuzzing** | 🔒 Ultimate requis | Analyse les API pour trouver des bugs et vulnérabilités. |

## 📌 **Conclusion**
Certaines fonctionnalités de sécurité de GitLab nécessitent un abonnement **Ultimate**. Pour une sécurité optimale, il est recommandé d’activer **SAST, DAST et Dependency Scanning** et d’ajouter un scanner de conteneurs si vous utilisez Docker.

---
🚀 **Besoin d’aide pour configurer ces outils ?** Consultez la [documentation officielle](https://docs.gitlab.com/ee/user/application_security/).

