# Text Generator
Text generator. Made for Tinkoff education.

# howto
пишу на русском т.к. могу и хочу.\
вообщем чтобы сохранить натреннированую модель пишите в терминал train.py <текст для обучения (датасет)> <куда сохранять>
а чтобы сгенерировать текст пишите generate.py [длина текста (70 по умолчанию)] [seed для генерации (рандомный по умолчанию)] <путь к модели>

# howto in code
а также можете импортить папку как модель и использовать класс TextGenerator, при инициализации укажите text_path и store_path для текста и куда сохранять модель.\
сама generate() для генерации текста, set_(имя переменной) чтобы изменить имя переменной, store() чтобы сохранить модель, fit() чтобы тренить модель, вроде все\
это ридми ужасно, скорее всего я потом его пофикшу

# additional

made for tinkoff education or smthing\
everything in english because why not