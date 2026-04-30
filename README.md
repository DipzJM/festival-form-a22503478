# festival

Descreva aqui as alterações/correções que fez
adicionei .order_by('data') no dia_view para ordenar
ordering = ["dia__data", "hora"] ordena dentro de cada dia os eventos por hora e data
foi adicionado no forms.py no ConcertoForm mudei o campo fields e inseri '__all__' para conseguir editar todos os campos
foi criado 2 url no urls.py para apagar e para criar um concerto e nas views.py foi feito um from  no criar_concerto.html

criei uma view/url para editar o placo