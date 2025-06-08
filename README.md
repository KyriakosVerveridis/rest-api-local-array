# REST API με Local Array

Αυτό το έργο είναι ένα απλό REST API backend φτιαγμένο με Node.js και Express, το οποίο χρησιμοποιεί ένα τοπικό array για αποθήκευση δεδομένων στη μνήμη (χωρίς βάση δεδομένων). Περιλαμβάνει παραδείγματα CRUD (Create, Read, Update, Delete) και μπορεί να δοκιμαστεί εύκολα με Postman ή άλλο REST client.

---

## 🔧 Τεχνολογίες / Εξαρτήσεις

- Node.js
- Express
- EJS (προαιρετικά για rendering templates)
- Body-Parser (για parsing request bodies)

---

## ⚙️ Εγκατάσταση και Εκτέλεση

### 1️⃣ Κλωνοποίησε το αποθετήριο:
```bash
git clone https://github.com/TO_USERNAME/rest-api-local-array.git


2️⃣ Πήγαινε στον φάκελο του έργου:
cd rest-api-local-array

3️⃣ Εγκατάστησε τις εξαρτήσεις:
npm install

4️⃣ Τρέξε τον διακομιστή:
node index.js

ή με nodemon (αν έχεις εγκατεστημένο):
npx nodemon index.js

📦 Εξαρτήσεις (dependencies)
express — βασικό framework για το API

ejs — για rendering templates (αν υπάρχει frontend)

body-parser — για ανάγνωση των req.body σε POST/PATCH

✍️ Περιγραφή API
Το API περιλαμβάνει endpoints για:

Μέθοδος	Endpoint	Περιγραφή
GET	/jokes	Επιστρέφει όλα τα ανέκδοτα
POST	/jokes	Προσθέτει νέο ανέκδοτο
PATCH	/jokes/:id	Επεξεργάζεται ανέκδοτο
DELETE	/jokes/:id	Διαγράφει ανέκδοτο

🧪 Δοκιμή με Postman
Κάνε HTTP αιτήματα στο http://localhost:3000/jokes

Παράδειγμα POST ή PATCH:
{
  "text": "Το νέο ανέκδοτο",
  "type": "funny"
}


✅ Ιδανικό για:
Εξάσκηση σε REST APIs
Παραδείγματα CRUD χωρίς βάση δεδομένων
Χρήση με Postman
Εκπαιδευτικά demo

Καλή εξάσκηση! 🚀
