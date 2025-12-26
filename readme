<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basketball Stats Pro - 取扱説明書</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif;
            background-color: #121212;
            color: #e0e0e0;
            line-height: 1.6;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        h1 {
            font-size: 2.2rem;
            font-weight: 900;
            margin-bottom: 1rem;
            color: #fff;
            border-bottom: 2px solid #3b82f6;
            padding-bottom: 10px;
        }
        h2 {
            font-size: 1.5rem;
            font-weight: 700;
            margin-top: 2.5rem;
            margin-bottom: 1rem;
            color: #3b82f6;
            border-left: 4px solid #3b82f6;
            padding-left: 10px;
        }
        h3 {
            font-size: 1.2rem;
            font-weight: 700;
            margin-top: 1.5rem;
            margin-bottom: 0.5rem;
            color: #eab308;
        }
        p {
            margin-bottom: 1rem;
        }
        ul, ol {
            margin-bottom: 1rem;
            padding-left: 1.5rem;
        }
        ul { list-style-type: disc; }
        ol { list-style-type: decimal; }
        li { margin-bottom: 0.5rem; }
        
        .box {
            background-color: #1e1e1e;
            border: 1px solid #333;
            border-radius: 8px;
            padding: 20px;
            margin-bottom: 20px;
        }
        .warn {
            border-left: 4px solid #ef4444;
            background-color: rgba(239, 68, 68, 0.1);
        }
        .info {
            border-left: 4px solid #22c55e;
            background-color: rgba(34, 197, 94, 0.1);
        }
        
        .btn-mock {
            display: inline-block;
            background: #333;
            color: white;
            padding: 2px 8px;
            border-radius: 4px;
            font-size: 0.8rem;
            font-weight: bold;
            border: 1px solid #555;
        }
        
        .icon {
            display: inline-block;
            width: 1.2em;
            height: 1.2em;
            vertical-align: text-bottom;
        }

        /* Print styles */
        @media print {
            body { background: white; color: black; }
            .box { border: 1px solid #ccc; background: white; }
            h1, h2, h3 { color: black; border-color: black; }
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Basketball Stats Pro 取扱説明書</h1>
    <p>この度は「Basketball Stats Pro」をご利用いただきありがとうございます。<br>本アプリは、バスケットボールの試合データを直感的に記録・分析・保存するためのツールです。</p>

    <div class="box info">
        <strong>💡 オフラインで動作します</strong><br>
        このアプリは一度ページを開けば、インターネット接続がない環境（体育館や機内モードなど）でも完全に動作します。通信量を気にせずご利用いただけます。
    </div>

    <div class="box info">
        <strong>🔒 安心のデータ管理</strong><br>
        入力したデータ（チーム情報、試合履歴）は、すべて<strong>お使いの端末（ブラウザ）の中にのみ</strong>保存されます。外部のサーバーに送信されることは一切ないため、プライバシーや機密情報が流出する心配はありません。
    </div>

    <h2>📱 スマートフォンでの利用方法 (iOS/Android)</h2>
    <p>このアプリはWebブラウザで動作しますが、「ホーム画面に追加」機能を使うことで、アプリのように全画面で快適に利用できます。</p>

    <h3>iPhone / iPad (iOS) の場合</h3>
    <ol>
        <li>Safariでこのページを開きます。</li>
        <li>画面下部（iPadは上部）の<strong>共有アイコン</strong> <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M4 12v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-8"/><polyline points="16 6 12 2 8 6"/><line x1="12" y1="2" x2="12" y2="15"/></svg> をタップします。</li>
        <li>メニューをスクロールして<strong>「ホーム画面に追加」</strong>を選択します。</li>
        <li>右上の「追加」をタップします。</li>
        <li>ホーム画面に追加されたアイコンから起動すると、アドレスバーが消え、アプリとして利用できます。</li>
    </ol>

    <h3>Android (Chrome) の場合</h3>
    <ol>
        <li>Chromeでこのページを開きます。</li>
        <li>右上のメニューアイコン（︙）をタップします。</li>
        <li><strong>「ホーム画面に追加」</strong>または<strong>「アプリをインストール」</strong>を選択します。</li>
    </ol>

    <div class="box warn">
        <strong>⚠️ データの消失にご注意ください</strong><br>
        データはブラウザの保存領域（LocalStorage）を使用しています。以下の操作を行うとデータが消える可能性があります。
        <ul>
            <li>ブラウザの「履歴とWebサイトデータを消去」を行う。</li>
            <li>「プライベートブラウズモード（シークレットモード）」で使用し、タブを閉じる。</li>
            <li>アプリ（ホーム画面のアイコン）を削除する。</li>
        </ul>
        重要なデータはこまめにPDF保存することをお勧めします。
    </div>

    <h2>🏀 基本的な使い方</h2>

    <h3>1. チームの登録</h3>
    <p>最初にチームと選手を登録します。</p>
    <ol>
        <li>スタート画面の <span class="btn-mock">TEAMS</span> ボタンをタップします。</li>
        <li><span class="btn-mock">+ CREATE NEW TEAM</span> で新しいチームを作成します。</li>
        <li>作成されたチームの <span class="btn-mock">EDIT</span> ボタンを押します。</li>
        <li>チーム名と、選手の背番号・名前を入力します。<span class="btn-mock">+ ADD</span> で選手を追加できます。</li>
    </ol>

    <h3>2. 試合の開始</h3>
    <ol>
        <li>スタート画面で「INFO（日付・試合名）」を入力します。</li>
        <li>「MATCHUP」でホームチームとアウェイチームを選択します。</li>
        <li><span class="btn-mock">START GAME</span> ボタンで試合画面へ移動します。</li>
    </ol>

    <h3>3. 試合中の記録（入力操作）</h3>
    <p><strong>基本的な流れ: 「誰が」→「何をした」</strong></p>
    <ul>
        <li><strong>選手選択:</strong> 画面上下の選手リスト（横スクロール可能）から、該当する選手をタップします。選択中の選手はハイライトされます。</li>
        <li><strong>プレイ選択:</strong> 画面中央のボタン（3P, 2P, REB, ASTなど）をタップします。</li>
        <li><strong>キャンセル:</strong> 間違えた場合は <span class="btn-mock">↩️ UNDO</span> ボタンで直前の操作を取り消せます。</li>
    </ul>
    
    <p><strong>その他の操作:</strong></p>
    <ul>
        <li><strong>クォーター変更:</strong> スコアボード中央の「Q1」などをタップして変更します。</li>
        <li><strong>タイムアウト:</strong> スコアボード横の <span class="btn-mock">TO</span> ボタンをタップします（前半2回、後半3回などの制限あり）。</li>
        <li><strong>選手交代:</strong> 交代したいチームの選手リスト右端にある <span class="btn-mock">SUB</span> ボタン、または中央パネルの <span class="btn-mock">SUB</span> ボタンを押します。コートに出る選手とベンチに下がる選手を選択して交代します。</li>
    </ul>

    <h3>4. 試合終了と保存</h3>
    <ol>
        <li>試合が終わったら、画面右下の <span class="btn-mock">終了アイコン</span> をタップします。</li>
        <li>「SAVE & EXIT」を選択すると、履歴に保存されてスタート画面に戻ります。</li>
    </ol>

    <h2>📄 履歴とレポート出力</h2>
    <p>保存した試合結果を確認・印刷できます。</p>
    <ol>
        <li>スタート画面の <span class="btn-mock">HISTORY</span> ボタンをタップします。</li>
        <li>見たい試合を選択して <span class="btn-mock">VIEW ></span> をタップします。</li>
        <li>詳細なスタッツ表が表示されます。</li>
        <li>右上の <span class="btn-mock">Print / PDF</span> ボタンを押すと、印刷プレビューが開きます。</li>
        <li>プリンターで印刷するか、スマホの機能で「ファイルに保存（PDF）」を選択して保存してください。</li>
    </ol>

    <h2>❓ よくある質問</h2>
    <dl>
        <dt class="font-bold text-blue-400 mt-2">Q. データ移行はできますか？</dt>
        <dd class="ml-4 mb-2">A. 現バージョンでは、異なる端末へのデータ移行機能はありません。端末ごとにデータが管理されます。</dd>

        <dt class="font-bold text-blue-400 mt-2">Q. アプリを閉じたらデータは消えますか？</dt>
        <dd class="ml-4 mb-2">A. いいえ、自動的に保存されています。再度ページを開けば続きから利用できます（ブラウザのキャッシュをクリアしない限り残ります）。</dd>

        <dt class="font-bold text-blue-400 mt-2">Q. 得点が2点入ったのに3点になってしまった</dt>
        <dd class="ml-4 mb-2">A. <span class="btn-mock">↩️ UNDO</span> ボタンを押して前の状態に戻し、正しいボタンを押し直してください。</dd>
    </dl>

    <hr class="my-8 border-gray-700">
    <footer class="text-center text-gray-500 text-sm">
        &copy; 2024 Basketball Stats Pro
    </footer>
</div>

</body>
</html>

