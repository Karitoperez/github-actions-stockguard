# github-actions-stockguard

Repositorio de práctica para aprender GitHub Actions (CI con Python y pytest).
Caso: StockGuard, clasificación del nivel de riesgo de inventario.

## Reglas
- Stock 0: AGOTADO
- Stock <= 50 % del mínimo: CRITICO
- Stock <= mínimo: BAJO
- Otro caso: NORMAL
- Stock negativo o mínimo <= 0: inválido (ValueError)

## Probar localmente
```
python -m pip install -r requirements.txt
pytest -v
```
