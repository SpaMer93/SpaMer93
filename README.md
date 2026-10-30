# Javier Cuevas

### IA aplicada: modelos locales, agentes y automatización

Ensenada, Baja California. Vengo del soporte técnico y la seguridad, y terminé construyendo y operando sistemas de IA de punta a punta. Eso significa que no solo monto el modelo: también me toca el respaldo, el servicio que se cae a las tres de la mañana y el usuario que no encuentra el botón.

Los repositorios de aquí son exhibición, no código abierto. Documentan cómo están hechas las cosas, qué se midió y qué salió mal. El código vive en privado; se comparte por conversación.

## Lo que hay publicado

| Repo | De qué va |
|---|---|
| [agent-cost-optimization](https://github.com/SpaMer93/agent-cost-optimization) | Dónde se va el dinero de un agente de IA. Cuatro etapas de medición sobre un agente real, con la evidencia cruda y una conclusión que no me gustó. |
| [passbolt-selfhosted](https://github.com/SpaMer93/passbolt-selfhosted) | Gestor de contraseñas auto-hospedado para un equipo. Red privada, TLS real, respaldo externo verificado y una recuperación probada en un apagón real. |
| [renascor-hub](https://github.com/SpaMer93/renascor-hub) | Portal que indexa 643 documentos de 18 proyectos y contesta "¿en qué quedó esto?" sin inventarse estados. |

## Cómo trabajo

Mido antes de optimizar, y cuando la medición contradice mi hipótesis, publico la contradicción. Prefiero un sistema con menos piezas que uno elegante: cada componente que agregas es uno más que se cae solo. Y si algo no lo puedo comprobar, lo digo en vez de suponerlo.

## Con qué trabajo

**IA y modelos**: modelos abiertos en local (Llama, Qwen, Gemma) con Ollama, llama.cpp y vLLM, elección por VRAM y cuantización GGUF, *function calling*, agentes con memoria persistente, voz de punta a punta (Whisper → LLM → TTS).

**Desarrollo**: Python, Bash, APIs REST y endpoints compatibles con OpenAI, Docker y Docker Compose, Git.

**Infraestructura**: Linux y systemd, Tailscale, TLS, respaldos cifrados con verificación de restauración, segmentación de red.

## Contacto

[javier.cucj93@gmail.com](mailto:javier.cucj93@gmail.com)

© 2026 Javier Cuevas. La documentación se publica como exhibición; el código no se distribuye.
