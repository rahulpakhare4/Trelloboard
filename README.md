<!DOCTYPE html>
<!-- saved from url=(0080)https://great-learning.s3.ap-south-1.amazonaws.com/week-2/trello-dashboard.html? -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
        
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta http-equiv="X-UA-Compatible" content="ie=edge">
        <title>Trello Board</title>
        <link rel="stylesheet" href="./Trello Board_files/reset.css">
        <link rel="stylesheet" href="./Trello Board_files/utils.css">
        <link rel="stylesheet" href="./Trello Board_files/trello-dashboard.css">
        <link rel="stylesheet" href="./Trello Board_files/trello-board.css">
        <link href="./Trello Board_files/css/all.css" rel="stylesheet">
        <!--
            Downloaded from https://fontawesome.com/how-to-use/on-the-web/setup/hosting-font-awesome-yourself
        -->
        <link rel="stylesheet" href="./Trello Board_files/all.min.css">
    </head>
    <body>
        <nav class="navbar">
            <ul class="menu">
                <li class="pointer">
                    <i class="home fas fa-home"></i>
                </li>
                <li class="pointer">
                    <i class="boards fas fa-th-list"></i>
                    Boards
                </li>
                <li class="menu-input">
                    <input type="text">
                </li>
            </ul>
            <div class="app-title">
                Tralala
            </div>
            <div class="actions">
                <span class="pointer">
                    <i class="fas fa-plus" id="add-board"></i>
                </span>
                <span class="pointer">
                    <i class="fas fa-user" id="profile-image"></i>
                </span>
            </div>
        </nav>
        <div class="board-container">
            <div class="board-menu">
                <div class="board-title">Frontend Training</div>
                <div class="board-show-menu pointer">
                    <i class="fas fa-ellipsis-v"></i>
                    Show menu
                </div>
            </div>
            <div class="board">
                <div class="task-list-wrapper">
                    <div class="task-list">
                        <div class="task-list-title-container">
                            <h3 class="task-list-title">To Do</h3>
                            <span class="task-list-more pointer">...</span>
                        </div>
                        <div class="task pointer">
                            Learn HTML
                            <i class="task-edit fas fa-pencil-alt pointer"></i>
                        </div>
                        <div class="task pointer">
                            Learn CSS
                            <i class="task-edit fas fa-pencil-alt pointer"></i>
                        </div>
                        <div class="task pointer">
                            Learn JavaScript
                            <i class="task-edit fas fa-pencil-alt pointer"></i>
                        </div>
                        <div class="add-card-message pointer">+ Add another card</div>
                    </div>
                </div>
                <div class="task-list-wrapper">
                    <div class="task-list">
                        <div class="task-list-title-container">
                            <h3 class="task-list-title">Doing</h3>
                            <span class="task-list-more pointer">...</span>
                        </div>
                        <div class="task pointer">Prepare resume</div>
                        <div class="add-card-form">
                            <form>
                                <textarea rows="3" placeholder="Enter a title for this card..." class="full-width-input"></textarea>
                                <div class="add-card-form-actions">
                                    <button class="btn btn-inline btn-primary add-card-button pointer">Add Card</button>
                                    <i class="fas fa-2x fa-times add-card-cancel pointer"></i>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
                <div class="task-list-wrapper">
                    <div class="task-list">
                        <div class="task-list-title-container">
                            <h3 class="task-list-title">Testing/Verifying</h3>
                            <span class="task-list-more pointer">...</span>
                        </div>
                        <div class="task pointer">Twitter app frontend</div>
                        <div class="add-card-message pointer">+ Add another card</div>
                    </div>
                </div>
                <div class="task-list-wrapper">
                    <div class="task-list">
                        <div class="task-list-title-container">
                            <h3 class="task-list-title">Deploying</h3>
                            <span class="task-list-more pointer">...</span>
                        </div>
                        <div class="task pointer">Twitter app backend</div>
                        <div class="add-card-message pointer">+ Add another card</div>
                    </div>
                </div>
                <div class="task-list-wrapper">
                    <div class="task-list">
                        <div class="task-list-title-container">
                            <h3 class="task-list-title">Done</h3>
                            <span class="task-list-more pointer">...</span>
                        </div>
                        <div class="add-card-message pointer">+ Add card</div>
                    </div>
                </div>
                <div class="task-list-wrapper">
                    <div class="task-list">
                        <div class="add-list-message pointer">+ Add another list</div>
                    </div>
                </div>
                <div class="task-list-wrapper">
                    <div class="task-list">
                        <div class="add-card-form">
                            <form>
                                <textarea rows="3" placeholder="Enter list title..." class="full-width-input"></textarea>
                                <div class="add-list-form-actions">
                                    <button class="btn btn-inline btn-primary add-list-button pointer">Add List</button>
                                    <i class="fas fa-2x fa-times add-list-cancel pointer"></i>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    
</body></html>
