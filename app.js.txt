body {
  font-family: Arial, sans-serif;
  background-color: #f4f7fa;
  margin: 0;
  padding: 0;
}

.container {
  max-width: 600px;
  margin: 50px auto;
  padding: 30px;
  background: white;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

h1 {
  color: #333;
  text-align: center;
}

p {
  text-align: center;
  color: #666;
}

form {
  display: flex;
  flex-direction: column;
}

.input-section {
  margin-bottom: 20px;
}

label {
  margin-top: 10px;
  font-weight: bold;
}

input {
  padding: 10px;
  margin-top: 5px;
  border-radius: 5px;
  border: 1px solid #ccc;
  font-size: 16px;
}

button {
  margin-top: 15px;
  padding: 12px;
  background-color: #007bff;
  color: white;
  font-size: 16px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

button:hover {
  background-color: #0056b3;
}

.result-box {
  margin-top: 30px;
  padding: 20px;
  background-color: #e9f7ef;
  border-left: 5px solid #28a745;
  color: #155724;
  display: none;
}

.debt-row,
.goal-row {
  display: flex;
  gap: 10px;
  margin-bottom: 10px;
}