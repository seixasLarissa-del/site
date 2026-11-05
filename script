// Exibe a janela modal com as informações do card selecionado
function mostrarInfo(titulo, descricao) {
  const modal = document.getElementById('modal');
  const modalTitle = document.getElementById('modal-title');
  const modalDesc = document.getElementById('modal-desc');

  modalTitle.textContent = titulo;
  modalDesc.textContent = descricao;

  modal.classList.remove('hidden');
}

// Fechar a modal ao clicar no botão 'X'
document.getElementById('close-modal').addEventListener('click', () => {
  document.getElementById('modal').classList.add('hidden');
});

// Fechar a modal ao clicar fora da caixa de conteúdo
window.addEventListener('click', (event) => {
  const modal = document.getElementById('modal');
  if (event.target === modal) {
    modal.classList.add('hidden');
  }
});

// Suporte para fechar a modal com a tecla ESC
window.addEventListener('keydown', (event) => {
  if (event.key === 'Escape') {
    document.getElementById('modal').classList.add('hidden');
  }
});