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
  "//": "BR Item Shop Config",
  "daily1": {
      "itemGrants": [""],
      "price": 0
  },
  "daily2": {
      "itemGrants": [""],
      "price": 0
  },
  "daily3": {
      "itemGrants": [""],
      "price": 10
  },
  "daily4": {
      "itemGrants": [""],
      "price": 0
  },
  "daily5": {
      "itemGrants": [""],
      "price": 0
  },
  "featured1": {
      "itemGrants": [""],
      "price": 0
  },
  "featured2": {
      "itemGrants": [""],
      "price": 0
  },
  "featured3": {
      "itemGrants": [""],
      "price": 0
  },
  "featured4": {
      "itemGrants": [""],
      "price": 0
  }
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
  "daily1": {
      "itemGrants": ["AthenaDance:EID_TakeTheL"],
      "price": 3000
  },
  "daily2": {
      "itemGrants": ["AthenaDance:EID_HappySkipping"],
      "price": 3000
  },
  "daily3": {
      "itemGrants": ["AthenaPickaxe:Pickaxe_ID_020_Keg"],
      "price": 1500
  },
  "daily4": {
      "itemGrants": ["AthenaBackpack:BID_229_LuckyRiderMale"],
      "price": 1500
  },
  "daily5": {
      "itemGrants": ["AthenaCharacter:CID_717_Athena_Commando_F_BlueFlames"],
      "price": 2500
  },
  "featured1": {
      "itemGrants": ["AthenaCharacter:CID_716_Athena_Commando_M_BlueFlames"],
      "price": 2500
  },
  "featured2": {
      "itemGrants": ["AthenaCharacter:CID_709_Athena_Commando_F_BandolierSlurp"],
      "price": 2600
  },
  "featured3": {
      "itemGrants": ["AthenaCharacter:CID_570_Athena_Commando_M_SlurpMonster"],
      "price": 2600
  },
  "featured4": {
      "itemGrants": ["AthenaCharacter:CID_616_Athena_Commando_F_CavalryBandit"],
      "price": 1800
  }
}
```

---

### ✅ Lista de Verificação Final

- ✔️ Certifique-se de que todos os cosméticos são da Temporada 2 do Capítulo 2 (Versão 12.41) ou anterior.
- ✔️ Use o formato correto de ID de Cosmético.
- ✔️ Correspondência dos preços em V-Bucks com os preços oficiais do Fortnite.
- ✔️ Verifique se há erros de digitação na configuração.


