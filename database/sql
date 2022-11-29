-- phpMyAdmin SQL Dump
-- version 3.5.2.2
-- http://www.phpmyadmin.net
--
-- Хост: localhost
-- Время создания: Янв 12 2017 г., 22:49
-- Версия сервера: 5.6.33-79.0
-- Версия PHP: 5.3.28

SET SQL_MODE="NO_AUTO_VALUE_ON_ZERO";
SET time_zone = "+00:00";


/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8 */;

--
-- База данных: `biblioteka`
--
CREATE DATABASE `biblioteka` DEFAULT CHARACTER SET utf8 COLLATE utf8_general_ci;
USE `biblioteka`;

-- --------------------------------------------------------

--
-- Структура таблицы `books`
--

CREATE TABLE IF NOT EXISTS `books` (
  `id` smallint(6) NOT NULL AUTO_INCREMENT COMMENT 'ID материала',
  `author_firstname` varchar(30) DEFAULT NULL COMMENT 'Автор: имя',
  `author_secondname` varchar(30) DEFAULT NULL COMMENT 'Автор: фамилия',
  `author_thirdname` varchar(30) DEFAULT NULL COMMENT 'Автор: отчество',
  `speciality` varchar(100) DEFAULT NULL COMMENT 'Специальность',
  `leader_firstname` varchar(30) DEFAULT NULL COMMENT 'Руководитель: имя',
  `leader_secondname` varchar(30) DEFAULT NULL COMMENT 'Руководитель: фамилия',
  `leader_thirdname` varchar(30) DEFAULT NULL COMMENT 'Руководитель: отчество',
  `title` varchar(250) DEFAULT NULL COMMENT 'Заголовок',
  `link` varchar(100) DEFAULT NULL COMMENT 'Ссылка на материал',
  `year` smallint(4) NOT NULL DEFAULT '0' COMMENT 'Год публикации',
  `category_id` tinyint(4) NOT NULL DEFAULT '0' COMMENT 'Тип работы',
  `date_add` datetime DEFAULT '0000-00-00 00:00:00' COMMENT 'Дата добавления',
  PRIMARY KEY (`id`),
  KEY `year` (`year`),
  KEY `speciality` (`speciality`)
) ENGINE=InnoDB  DEFAULT CHARSET=utf8 COMMENT='Работы студентов' AUTO_INCREMENT=17 ;

--
-- Дамп данных таблицы `books`
--

INSERT INTO `books` (`id`, `author_firstname`, `author_secondname`, `author_thirdname`, `speciality`, `leader_firstname`, `leader_secondname`, `leader_thirdname`, `title`, `link`, `year`, `category_id`, `date_add`) VALUES
(7, 'Анна', 'Сабурова', 'Викторовна', 'Журналистика', 'Николай', 'Лигитов', 'Юрьевич', 'Анализ шрифтов детской печатной продукции', 'https://mega.nz/#!W4820IqD!5c7utENqpWfDpzrtapCHiq86CFW0vYxNLxZwkiGSRg4', 2014, 3, '2016-03-17 15:47:06'),
(8, 'Игорь', 'Азаров', 'Александрович', 'Прикладная информатика', 'Анатолий', 'Мартынов', 'Федорович', 'Описание АБИС ИРБИС', 'https://mega.nz/#!molWlaID!SB8KCtugAr8K_D2mFheWuqglULWC7OKl3coFVP9ewbM', 2015, 2, '2016-03-17 15:50:02'),
(9, 'Мария', 'Богданова', 'Александровна', 'Прикладная информатика', 'Александр', 'Спицын', 'Валентинович', 'Разработка базы данных для Видеозала', 'https://mega.nz/#!rx0DhLLD!j3HXSQHPtMhBmByKA1cna9H8YSL2JbUisMp1UfrjJnI', 2016, 2, '2016-03-17 15:51:46'),
(10, 'Юлия', 'Комарова', 'Викторовна', 'Прикладная информатика', 'Александр', 'Спицын', 'Валентинович', 'Разработка базы данных Выставочного центра', 'https://mega.nz/#!y1N0SQSA!Np0fWxJJ7Y6I9et25032Csmc7pAejX5gKPbUCUyIBbw', 2016, 2, '2016-03-17 15:53:17'),
(11, 'Владислав', 'Тетерин', 'Игоревич', 'Прикладная информатика', 'Лидия', 'Путькина', 'Владимировна', 'Проектирование ИС Малый театр', 'https://mega.nz/#!vl0wwQTZ!Qqwq3DBDkpObG3GjLBW-WKHrmR3jga0GMWqPoD0obps', 2014, 2, '2016-03-17 15:55:00'),
(12, 'Алексей', 'Авилов', 'Дмитриевич', 'Прикладная информатика', 'Лариса', 'Попова', 'Дмитриевна', 'Экологические проблемы Казахстана', 'https://mega.nz/#!30l3VBgL!DJjXY8XeXFEvwf5a5tjppzomt4rSBqKvRade0DPv2SM', 2014, 1, '2016-03-17 15:56:59'),
(13, 'Анастасия', 'Агеева', 'Сергеевна', 'Прикладная информатика', 'Марина', 'Лигова', 'Александровна', 'Применение информационного подхода к функционированию web-сайта', 'https://mega.nz/#!rxVRiDxA!U3OhgntQFotm1b4BhnNbCXfJfe-CvBHTX3H14AIGYxE', 2014, 1, '2016-03-17 15:58:22'),
(14, 'Андрей', 'Агапов', 'Сергеевич', 'Финансы и кредит', 'Светлана', 'Липатова', 'Николаевна', 'Краткосрочная финансовая политика российских банков', 'https://mega.nz/#!jwczGa5B!qsb8H3K7XZjeqyVJXjAEMeNlFdcfJr0FFv4a8A2fxBo', 2015, 3, '2016-03-17 16:33:20'),
(15, 'Ирина', 'Яскевич', 'Владимировна', 'Финансы и кредит', 'Юлия', 'Войтукевич', 'Анатольевна', 'Кредитование торгового предприятия', 'https://mega.nz/#!ulVk2CRJ!0i8RhGx3QkFCDgTsLAtw4tjGB82BfYtGVlNsKjyLl4o', 2016, 3, '2016-03-17 16:41:41'),
(16, 'Константин', 'Иванов', 'Андреевич', 'Финансы и кредит', 'Светлана', 'Липатова', 'Дмитриевна', 'Кредитная политика коммерческого банка на примере &quot;Народный банк Казахстана&quot;', 'https://mega.nz/#!rpdVzTSK!_gDB9bvByw8iEoz-yopmK0m0DRFxqTrXHAZddySAnhw', 2015, 3, '2016-03-17 16:55:58');

-- --------------------------------------------------------

--
-- Структура таблицы `categories`
--

CREATE TABLE IF NOT EXISTS `categories` (
  `id` tinyint(3) unsigned NOT NULL AUTO_INCREMENT COMMENT 'ID категории',
  `code` varchar(20) DEFAULT NULL COMMENT 'Код',
  `name` varchar(50) DEFAULT NULL COMMENT 'Название',
  `search` varchar(60) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB  DEFAULT CHARSET=utf8 COMMENT='Категории материалов' AUTO_INCREMENT=4 ;

--
-- Дамп данных таблицы `categories`
--

INSERT INTO `categories` (`id`, `code`, `name`, `search`) VALUES
(1, 'scientific', 'Научная работа', 'Поиск научных работ'),
(2, 'term', 'Курсовая работа', 'Поиск курсовых работ'),
(3, 'thesis', 'Выпускная квалификационная работа', 'Поиск выпускных квалификационных работ');

-- --------------------------------------------------------

--
-- Структура таблицы `groups`
--

CREATE TABLE IF NOT EXISTS `groups` (
  `id` tinyint(3) unsigned NOT NULL AUTO_INCREMENT,
  `group_name` varchar(30) DEFAULT NULL,
  `user_name` varchar(30) DEFAULT NULL,
  `group_name_plural` varchar(30) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB  DEFAULT CHARSET=utf8 COMMENT='Группы пользователей' AUTO_INCREMENT=3 ;

--
-- Дамп данных таблицы `groups`
--

INSERT INTO `groups` (`id`, `group_name`, `user_name`, `group_name_plural`) VALUES
(1, 'Сотрудники', 'Сотрудник', 'сотрудника'),
(2, 'Читатели', 'Читатель', 'читателя');

-- --------------------------------------------------------

--
-- Структура таблицы `news`
--

CREATE TABLE IF NOT EXISTS `news` (
  `id` smallint(5) unsigned NOT NULL AUTO_INCREMENT COMMENT 'ID новости',
  `title` varchar(150) DEFAULT NULL COMMENT 'Заголовок',
  `message` text COMMENT 'Текст',
  `date_add` datetime NOT NULL DEFAULT '0000-00-00 00:00:00' COMMENT 'Дата создания',
  PRIMARY KEY (`id`)
) ENGINE=InnoDB  DEFAULT CHARSET=utf8 COMMENT='Новости' AUTO_INCREMENT=10 ;

--
-- Дамп данных таблицы `news`
--

INSERT INTO `news` (`id`, `title`, `message`, `date_add`) VALUES
(1, 'Добро пожаловать в библиотечную систему', 'Мы запустились и готовы представить Вам миллионы документов для изучения: выпускные квалификационные работы, научные и курсовые работы, многое другое.', '2016-01-17 08:37:14'),
(7, 'В РЭУ проходит XXIV Студенческая научная конференция.', 'Студенческая научная конференция, проводимая в РЭУ с 1992 года, посвящена обсуждению актуальных проблем современного социального и гуманитарного знания. Данное мероприятие проходит в течение 5 дней на всех факультетах Университета (культуры, искусств, экономическом, юридическом, конфликтологии).\r\nЭта конференция, позволяющая талантливой студенческой молодежи проявить себя, часто становится первой ступенью в научном и профессиональном росте будущих специалистов. Подтверждением тому являются последующие достижения студентов РЭУ, получающие признание на всероссийских и международных научных конференциях и конкурсах.\r\nВсего в этот день в рамках всех 8 секций более 100 студентов выступили с докладами, вызвавшими интерес слушателей и дискуссии.', '2016-01-25 16:22:32'),
(8, 'VI Межвузовская научно-практическая конференция «Танец в диалоге культур и традиций».', 'Конференция проводится кафедрой хореографического искусства и является традиционной. В этом году конференция посвящена вопросам исследования танцевальных фольклорных традиций народов России, а также анализу проблем становления этнохореографии как науки.', '2016-02-03 11:20:07'),
(9, 'В журнале «Философия и культура» (№ 11, 2015) опубликована статья профессора кафедры философии и культурологии С.Б. Никоновой «Диалектика идеи нации».', 'Статья посвящена обзору Международных Лихачевских научных чтений, состоявшихся в Университете 14-15 мая 2015 года. В работе анализируется основная проблематика докладов, прозвучавших на Чтениях, делаются выводы об основных тенденциях обсуждения. Как основной проблемный момент всех докладов выявляется вопрос о сути идеи нации. Данная идея оказывается сложной и внутренне противоречивой, что связано со спецификой ее формирования и историей развития в современном обществе.', '2016-03-03 10:10:48');

-- --------------------------------------------------------

--
-- Структура таблицы `users`
--

CREATE TABLE IF NOT EXISTS `users` (
  `id` smallint(5) unsigned NOT NULL AUTO_INCREMENT COMMENT 'ID пользователя',
  `login` varchar(20) DEFAULT NULL COMMENT 'Логин',
  `password` varchar(32) DEFAULT NULL COMMENT 'Пароль',
  `group_id` tinyint(3) unsigned NOT NULL DEFAULT '3' COMMENT 'ID группы',
  `firstname` varchar(30) DEFAULT NULL COMMENT 'Имя',
  `secondname` varchar(30) DEFAULT NULL COMMENT 'Фамилия',
  `thirdname` varchar(30) DEFAULT NULL COMMENT 'Отчество',
  `email` varchar(50) DEFAULT NULL COMMENT 'Почта',
  `date_add` datetime DEFAULT '0000-00-00 00:00:00' COMMENT 'Дата добавления',
  `date_online` datetime DEFAULT '0000-00-00 00:00:00' COMMENT 'Последняя активность',
  PRIMARY KEY (`id`),
  UNIQUE KEY `login` (`login`)
) ENGINE=InnoDB  DEFAULT CHARSET=utf8 COMMENT='Пользователи' AUTO_INCREMENT=16 ;

--
-- Дамп данных таблицы `users`
--

INSERT INTO `users` (`id`, `login`, `password`, `group_id`, `firstname`, `secondname`, `thirdname`, `email`, `date_add`, `date_online`) VALUES
(5, 'Azarov', 'eec044b8c5f0d21b317a869dcb8d60e7', 1, 'Игорь', 'Азаров', 'Александрович', 'Azarov.Igor00@yandex.ru', '2016-03-17 08:26:51', '2016-05-25 18:39:47'),
(6, 'Admin', 'a5b0dcb1e0f15e087832c3b27e3d14d0', 1, 'Никита', 'Котов', 'Игоревич', 'admin@admin.ru', '2016-03-17 09:02:00', '2016-03-23 11:38:14'),
(10, 'Ivanov', '4a91e2d7272461d402b3fb55eb0bbb7a', 2, 'Андрей', 'Иванов', 'Сергеевич', '123@mail.ru', '2016-03-22 09:56:19', '2016-05-23 15:31:18'),
(15, 'demo', 'fa1b958537c0aaf8e621ef115d7e9627', 1, 'Дмитрий', 'Верхоумов', 'Олегович', 'verkhoumov@yandex.ru', '2016-05-30 02:06:10', '2017-01-12 22:06:38');

/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS */;
/*!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION */;
