# ⚠️ IMPORTANTE ⚠️  
Você pode achar todos os cosméticos do Fortnite em **[Fortnite.GG](https://fortnite.gg/cosmetics)**.

### Requisitos:
1. **Os cosméticos devem ser da Temporada 2 do Capítulo 2 (Versão 12.41) ou anterior.** (Qualquer coisa mais recente não funcionará.)
2. **Certifique-se de que os preços em V-Bucks correspondem aos preços originais do Fortnite.**
3. **Use o formato correto de ID de Cosmético.** (Caso contrário, os itens não funcionarão corretamente.)

---

## 🔧 Como Configurar Sua Loja de Itens

### **Passo 1: Entenda o Formato da Configuração**  
A configuração da loja de itens segue essa estrutura:

```json
{
    "//": "Configuração da Loja BR",
    "daily1": {"itemGrants": [""], "price": 0},
    "daily2": {"itemGrants": [""], "price": 0},
    "daily3": {"itemGrants": [""], "price": 0},
    "daily4": {"itemGrants": [""], "price": 0},
    "daily5": {"itemGrants": [""], "price": 0},
    "daily6": {"itemGrants": [""], "price": 0},
    "featured1": {"itemGrants": [""], "price": 0},
    "featured2": {"itemGrants": [""], "price": 0},
    "featured3": {"itemGrants": [""], "price": 0},
    "featured4": {"itemGrants": [""], "price": 0}            
}
```

---
## Passo 2: Use o Formato Correto de ID dos Cosméticos
Cada item no Fortnite tem um **ID de Cosmético** que deve seguir um formato específico.

#### ✅ Exemplo:  
Se o **ID de Cosmético** for `Character_NebulaFN` e for um traje, ela deve ser formatada como:  
```json
"AthenaCharacter:Character_NebulaFN"
```

#### 📌 **Formatação Correta por Tipo de Item:**
- **Skins:** `AthenaCharacter:CosmeticID`
- **Emotes:** `AthenaDance:CosmeticID` *(Includes Dances, Emoticons, Sprays)*
- **Pickaxes:** `AthenaPickaxe:CosmeticID`
- **Gliders:** `AthenaGlider:CosmeticID`
- **Wraps:** `AthenaItemWrap:CosmeticID`
- **Loading Screens:** `AthenaLoadingScreen:CosmeticID`
- **Skydiving Contrails:** `AthenaSkyDiveContrail:CosmeticID`


---

#### **Passo 3: Adicione itens a Sua Loja**

- **`itemGrants`**: Os itens que estarão disponíveis para compra, identificados pelo ID de Cosmético.
- **`price`**: O custo do item em V-Bucks (deve corresponder ao preço original do Fortnite).

#### ✅ Exemplo de Configuração de Loja de Itens:
```json
{
    "//": "BR Item Shop Config",
    "daily1": {"itemGrants": ["AthenaCharacter:Character_EonFN"], "price": 1200},
    "daily2": {"itemGrants": ["AthenaPickaxe:Pickaxe_EonFN"], "price": 800},
    "daily3": {"itemGrants": ["AthenaDance:Dance_Flare"], "price": 500},
    "daily4": {"itemGrants": ["AthenaItemWrap:Wrap_Galaxy"], "price": 300},
    "daily5": {"itemGrants": ["AthenaGlider:Glider_StarSurfer"], "price": 1500},
    "daily6": {"itemGrants": ["AthenaLoadingScreen:LoadingScreen_Galactic"], "price": 200},
    "featured1": {"itemGrants": ["AthenaCharacter:Character_Drift"], "price": 2000},
    "featured2": {"itemGrants": ["AthenaDance:Dance_DefaultDance"], "price": 200},
    "featured3": {"itemGrants": ["AthenaSkyDiveContrail:Contrail_Rainbow"], "price": 400},
    "featured4": {"itemGrants": ["AthenaItemWrap:Wrap_Camo"], "price": 600}
}
```

---

### ✅ Lista de Verificação Final

- ✔️ Certifique-se de que todos os cosméticos são da Temporada 2 do Capítulo 2 (Versão 12.41) ou anterior.
- ✔️ Use o formato correto de ID de Cosmético.
- ✔️ Correspondência dos preços em V-Bucks com os preços oficiais do Fortnite.
- ✔️ Verifique se há erros de digitação na configuração.


