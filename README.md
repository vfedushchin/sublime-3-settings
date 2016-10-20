# sublime-3-settings
sublime 3 settings

// Settings in here override those in "Default/Preferences.sublime-settings",
// and are overridden in turn by file type specific settings.
{
	//Всегда отображать положение видимой области на миникарте.
	"always_show_minimap_viewport": true,	
    // Автоматически закрывать теги в HTML и XML при наборе последовательности символов "</".
    "auto_close_tags": true,
    // Включить автокомплит.
    "auto_complete": true,
    // Подсветка парных тегов в HTML и XML.
    "match_tags": true,
    // Подсвечивать слова, соответствующие выделенному.
    "match_selection": true,
    // Подсвечивать измененные вкладки.
    "highlight_modified_tabs": true,
    // Перед сохранением добавлять пустую строку в конец файла.
    "ensure_newline_at_eof_on_save": true,
    // Включить прокрутку вкладок.
    "enable_tab_scrolling": true,
    // Отображать отступы
    "draw_indent_guides": "stackGuide",
    // Отображать символы пробелов.
    "draw_white_space": "all",
    // Определять, что используется в качестве отступов – пробелы или табуляции
    "detect_indentation": true,
    // Включить или выключить автоматические отступы.
    "auto_indent": true,
    // Автоматически добавлять закрывающую скобку, парную кавычку и так далее.
    "auto_match_enabled": true,
    //Удаляет лишние символы пробелов и табудяции при сохранении
    "trim_trailing_white_space_on_save": true,
    // Двойной клик полностью выделяет слов. Например название пХп переменной вместе с $
    "word_separators": "./\\()\"'-:,.;<>~!@#%^&*|+=[]{}`~?",
    // Кодировка по-умолчанию — «UTF-8»
    "default_encoding": "UTF-8",
    // Отображать в статусной строке кодировку файла.
    "show_encoding": true,
    // Отображать в статусной строке символ конца строки.
    "show_line_endings": true,
    // Символ переноса строки
    "default_line_ending": "LF",
    // Включить или выключить перенос строк.
    "word_wrap": true,
    // Принудительно делать перенос с указанного по счету символа.
    "wrap_width": 120,
    // Автоматически сохранять файл при потере фокуса.
    "save_on_focus_lost": true,
    // Количество пробелов, которое будет использовано вместо табуляции.
    "tab_size": 4,
    // Отображать рамку вокруг миникарты
    "draw_minimap_border": true,
    // Подсвечивать парные угловые скобки
    "match_brackets_angle": true,
    // Тип скролл бара.
    "overlay_scroll_bars": "enabled",
    // Открывать незакрытые файлы при каждом запуске программы
    "remember_open_files": true,
    //Удалять автоматически добавленные пробелы.
    "trim_automatic_white_space": true,
    //Запрещает автоматическую уонвертацию табов в пробела.
    "translate_tabs_to_spaces": false
}
