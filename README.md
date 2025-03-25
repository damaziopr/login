from flask import Flask, request, jsonfy
 
app = Flask(__name__)
 
@app.route('/')
def bem_vindo():
  return 'Bem-vindo! Servidor rodando'

if __name__ == '__main__':
  app.run (debug=True)
