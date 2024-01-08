# Aprenda React em 60 minutos

[Assistir aula completa](https://youtu.be/Dy_dQo_G1hw?si=pVhkvBZg0ja5d0nX)

## JSX

```
<main className="app-container">
      <h1 className="title">Lista de Tarefas</h1>

      <section className="add-note-section">
        <div className="add-note-container">
          <input className="note-input" placeholder="Nova nota" />
          <button className="save-button">Salvar</button>
        </div>
      </section>

      <section className="task-section">
        <h3>Tarefas a Realizar</h3>
        <ul className="task-list">
          <li className="task-item">
            <span>Tarefa 1</span>
            <button className="complete-button">Realizado</button>
            <button className="delete-button">Excluir</button>
          </li>
          <li className="task-item">
            <span>Tarefa 2</span>
            <button className="complete-button">Realizado</button>
            <button className="delete-button">Excluir</button>
          </li>
        </ul>
      </section>

      <section className="completed-tasks-section">
        <h3>Tarefas Realizadas</h3>
        <ul className="completed-task-list">
          <li className="completed-task-item">
            <span>Tarefa 3</span>
            <button className="return-button">Retornar</button>
            <button className="delete-button">Excluir</button>
          </li>
        </ul>
      </section>
    </main>
```

## CSS
```
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  margin: 0;
  background-color: #121212;
  color: #fff;
  display: flex;
  align-items: center;
  justify-content: center;
}

.app-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 20px;
  margin: 20px;
  max-width: 80%;
  width: 400px;
  background-color: #333;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.title {
  font-size: 24px;
  font-weight: bold;
  margin-bottom: 20px;
}

.add-note-section,
.task-section,
.completed-tasks-section {
  width: 100%;
  margin-bottom: 20px;
}

.add-note-container {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.note-input {
  width: 100%;
  padding: 10px;
  font-size: 16px;
  box-sizing: border-box;
  margin-bottom: 10px;
  border: 1px solid #555;
  border-radius: 4px;
  background-color: #444;
  color: #fff;
}

.save-button {
  width: 100%;
  padding: 10px;
  margin-top: 10px;
  font-size: 16px;
  background-color: #4caf50;
  color: white;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

.task-list,
.completed-task-list {
  list-style: none;
  padding: 0;
}

.task-item,
.completed-task-item {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 15px;
  background-color: #555;
  border: 1px solid #777;
  border-radius: 4px;
  margin-bottom: 10px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.task-item span,
.completed-task-item span {
  flex-grow: 1;
  margin-right: 10px;
}

.complete-button,
.return-button,
.delete-button {
  padding: 8px;
  font-size: 14px;
  cursor: pointer;
  border: none;
  border-radius: 4px;
  margin-left: 5px;
}

.complete-button {
  background-color: #4caf50;
  color: white;
}

.return-button {
  background-color: #2196f3;
  color: white;
}

.delete-button {
  background-color: #f44336;
  color: white;
}
```
