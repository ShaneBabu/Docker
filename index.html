<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>🎬 CineVibe | Book Movie Tickets</title>
  <!-- Google Font & Font Awesome for icons -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,400;14..32,500;14..32,600;14..32,700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', sans-serif;
      background: linear-gradient(145deg, #0b0d19 0%, #14182b 100%);
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 1.5rem;
    }

    /* main card */
    .booking-container {
      max-width: 1200px;
      width: 100%;
      background: rgba(18, 22, 40, 0.75);
      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
      border-radius: 2.5rem;
      padding: 2rem 2rem 2rem 2rem;
      box-shadow: 0 30px 50px rgba(0, 0, 0, 0.7), 0 0 0 1px rgba(255, 255, 255, 0.05);
      border: 1px solid rgba(255, 255, 255, 0.08);
      transition: all 0.3s;
    }

    /* header */
    .header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 2rem;
      flex-wrap: wrap;
      gap: 1rem;
    }

    .logo {
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .logo i {
      font-size: 2rem;
      color: #f5c518;
      filter: drop-shadow(0 0 8px rgba(245, 197, 24, 0.6));
    }

    .logo h1 {
      font-size: 1.9rem;
      font-weight: 700;
      letter-spacing: -0.5px;
      background: linear-gradient(135deg, #ffffff 0%, #e0e7ff 80%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
    }

    .logo span {
      background: linear-gradient(135deg, #f5c518, #ffb347);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      font-weight: 800;
    }

    .city-selector {
      background: rgba(255, 255, 255, 0.05);
      border: 1px solid rgba(255, 255, 255, 0.1);
      padding: 0.6rem 1.2rem;
      border-radius: 40px;
      display: flex;
      align-items: center;
      gap: 10px;
      color: #cfd5ff;
      font-weight: 500;
      cursor: pointer;
      transition: all 0.2s;
      backdrop-filter: blur(8px);
    }

    .city-selector i {
      color: #f5c518;
    }

    .city-selector:hover {
      background: rgba(245, 197, 24, 0.12);
      border-color: rgba(245, 197, 24, 0.4);
      transform: scale(1.02);
    }

    /* movie list */
    .movies-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1.5rem;
      margin-bottom: 2rem;
    }

    .movie-card {
      background: rgba(255, 255, 255, 0.03);
      border: 1px solid rgba(255, 255, 255, 0.06);
      border-radius: 1.8rem;
      padding: 1.4rem 1.2rem 1.2rem 1.2rem;
      display: flex;
      gap: 1rem;
      transition: all 0.3s ease;
      cursor: pointer;
      position: relative;
      overflow: hidden;
      backdrop-filter: blur(5px);
    }

    .movie-card::after {
      content: '';
      position: absolute;
      inset: 0;
      border-radius: 1.8rem;
      padding: 1px;
      background: linear-gradient(135deg, rgba(245, 197, 24, 0.3), transparent 50%);
      -webkit-mask: linear-gradient(#fff 0 0) content-box, linear-gradient(#fff 0 0);
      -webkit-mask-composite: xor;
      mask-composite: exclude;
      pointer-events: none;
    }

    .movie-card:hover {
      transform: translateY(-6px);
      background: rgba(255, 255, 255, 0.07);
      border-color: rgba(245, 197, 24, 0.3);
      box-shadow: 0 20px 30px -10px rgba(0, 0, 0, 0.6);
    }

    .movie-card.active {
      background: rgba(245, 197, 24, 0.12);
      border-color: #f5c518;
      box-shadow: 0 0 20px rgba(245, 197, 24, 0.2);
    }

    .movie-poster {
      width: 80px;
      height: 110px;
      background: linear-gradient(135deg, #1e243b, #0f1322);
      border-radius: 1rem;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 2.5rem;
      flex-shrink: 0;
      box-shadow: 0 6px 12px rgba(0, 0, 0, 0.5);
      color: #f5c518;
    }

    .movie-info {
      display: flex;
      flex-direction: column;
      justify-content: center;
      flex: 1;
    }

    .movie-info h3 {
      font-size: 1.2rem;
      font-weight: 700;
      color: #fff;
      margin-bottom: 4px;
      line-height: 1.3;
    }

    .movie-meta {
      display: flex;
      gap: 12px;
      font-size: 0.8rem;
      color: #a5aed1;
      margin-bottom: 8px;
    }

    .movie-meta i {
      font-size: 0.7rem;
      margin-right: 3px;
      color: #f5c518;
    }

    .rating {
      display: flex;
      align-items: center;
      gap: 6px;
      font-size: 0.8rem;
      color: #ffd966;
      font-weight: 600;
    }

    .rating i {
      color: #f5c518;
    }

    /* showtime & seat section */
    .booking-panel {
      background: rgba(0, 0, 0, 0.35);
      border-radius: 2rem;
      padding: 1.8rem;
      backdrop-filter: blur(10px);
      border: 1px solid rgba(255, 255, 255, 0.05);
      margin-top: 1rem;
      display: flex;
      flex-wrap: wrap;
      gap: 2.5rem;
      justify-content: space-between;
      align-items: flex-start;
    }

    .showtime-section {
      flex: 1 1 240px;
    }

    .section-label {
      font-size: 0.75rem;
      text-transform: uppercase;
      letter-spacing: 2px;
      color: #919bc0;
      font-weight: 600;
      margin-bottom: 1rem;
      display: flex;
      align-items: center;
      gap: 8px;
    }

    .section-label i {
      color: #f5c518;
      font-size: 0.9rem;
    }

    .time-slots {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
    }

    .time-btn {
      background: rgba(255, 255, 255, 0.05);
      border: 1px solid rgba(255, 255, 255, 0.12);
      color: #d0d9ff;
      padding: 0.8rem 1.4rem;
      border-radius: 40px;
      font-weight: 600;
      font-size: 0.95rem;
      cursor: pointer;
      transition: all 0.2s;
      display: flex;
      align-items: center;
      gap: 8px;
      backdrop-filter: blur(4px);
    }

    .time-btn i {
      font-size: 0.8rem;
      color: #b0b9e0;
    }

    .time-btn:hover {
      background: rgba(245, 197, 24, 0.2);
      border-color: rgba(245, 197, 24, 0.6);
      color: #fff;
      transform: scale(1.02);
    }

    .time-btn.selected {
      background: #f5c518;
      border-color: #f5c518;
      color: #0b0d19;
      font-weight: 700;
      box-shadow: 0 0 18px rgba(245, 197, 24, 0.5);
    }

    .time-btn.selected i {
      color: #0b0d19;
    }

    /* seats */
    .seats-section {
      flex: 1 1 380px;
    }

    .screen-indicator {
      text-align: center;
      margin-bottom: 1.2rem;
      position: relative;
    }

    .screen-indicator span {
      font-size: 0.7rem;
      letter-spacing: 4px;
      color: #7c84a8;
      font-weight: 500;
    }

    .screen-curve {
      width: 70%;
      height: 10px;
      background: linear-gradient(90deg, transparent, #f5c518, #f5c518, #f5c518, transparent);
      margin: 8px auto 0;
      border-radius: 50%;
      opacity: 0.5;
      filter: blur(3px);
    }

    .seat-grid {
      display: flex;
      flex-direction: column;
      gap: 10px;
      align-items: center;
      margin-bottom: 1.5rem;
    }

    .seat-row {
      display: flex;
      gap: 10px;
      justify-content: center;
      align-items: center;
    }

    .seat {
      width: 34px;
      height: 34px;
      border-radius: 10px 10px 6px 6px;
      background: #2a2f4a;
      border: 1px solid #3e4460;
      cursor: pointer;
      transition: all 0.15s;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 0.7rem;
      font-weight: 600;
      color: #8e97bf;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.4);
    }

    .seat:hover {
      background: #3d4468;
      border-color: #f5c518;
      transform: scale(1.08);
    }

    .seat.selected {
      background: #f5c518;
      border-color: #f5c518;
      color: #0b0d19;
      box-shadow: 0 0 14px #f5c518aa;
      font-weight: 700;
    }

    .seat.occupied {
      background: #2b1e2e;
      border-color: #4e354b;
      color: #5e4c5e;
      cursor: not-allowed;
      opacity: 0.6;
      box-shadow: none;
      pointer-events: none;
    }

    .seat.occupied::after {
      content: "✕";
      font-size: 0.7rem;
    }

    /* legend */
    .legend {
      display: flex;
      justify-content: center;
      gap: 24px;
      font-size: 0.7rem;
      color: #a0a9ce;
      margin-top: 6px;
    }

    .legend-item {
      display: flex;
      align-items: center;
      gap: 6px;
    }

    .legend-box {
      width: 16px;
      height: 16px;
      border-radius: 4px;
    }

    .legend-box.available {
      background: #2a2f4a;
      border: 1px solid #3e4460;
    }

    .legend-box.selected {
      background: #f5c518;
      border: 1px solid #f5c518;
    }

    .legend-box.occupied {
      background: #2b1e2e;
      border: 1px solid #4e354b;
    }

    /* action bar */
    .action-bar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      gap: 1.5rem;
      margin-top: 2rem;
      padding-top: 0.5rem;
      border-top: 1px solid rgba(255, 255, 255, 0.06);
    }

    .total-price {
      display: flex;
      flex-direction: column;
    }

    .total-price .label {
      font-size: 0.75rem;
      text-transform: uppercase;
      letter-spacing: 1px;
      color: #8891b5;
    }

    .total-price .amount {
      font-size: 2rem;
      font-weight: 800;
      color: #f5c518;
      line-height: 1.2;
      letter-spacing: -1px;
    }

    .total-price .amount small {
      font-size: 1rem;
      font-weight: 500;
      color: #a5aed1;
      margin-left: 5px;
    }

    .book-btn {
      background: linear-gradient(135deg, #f5c518, #e0a800);
      border: none;
      padding: 1rem 2.8rem;
      border-radius: 50px;
      font-weight: 800;
      font-size: 1rem;
      color: #0b0d19;
      cursor: pointer;
      transition: all 0.25s;
      display: flex;
      align-items: center;
      gap: 10px;
      box-shadow: 0 12px 24px -8px rgba(245, 197, 24, 0.5);
      letter-spacing: 0.3px;
    }

    .book-btn i {
      font-size: 1.1rem;
    }

    .book-btn:hover {
      transform: scale(1.03);
      box-shadow: 0 18px 30px -6px #f5c518;
      background: linear-gradient(135deg, #ffd93b, #f5c518);
    }

    .book-btn:active {
      transform: scale(0.98);
    }

    .book-btn:disabled {
      background: #4a4f6b;
      color: #7e86a8;
      box-shadow: none;
      cursor: not-allowed;
      transform: none;
    }

    .toast {
      position: fixed;
      bottom: 30px;
      right: 30px;
      background: #1e2338;
      border-left: 6px solid #f5c518;
      padding: 1rem 1.8rem;
      border-radius: 16px;
      color: #fff;
      font-weight: 500;
      box-shadow: 0 20px 30px rgba(0, 0, 0, 0.7);
      backdrop-filter: blur(8px);
      display: flex;
      align-items: center;
      gap: 12px;
      z-index: 999;
      transform: translateY(100px);
      opacity: 0;
      transition: transform 0.3s ease, opacity 0.3s ease;
      pointer-events: none;
      border: 1px solid rgba(245, 197, 24, 0.3);
    }

    .toast.show {
      transform: translateY(0);
      opacity: 1;
    }

    .toast i {
      color: #f5c518;
      font-size: 1.4rem;
    }

    /* responsive */
    @media (max-width: 750px) {
      .booking-container {
        padding: 1.5rem;
      }
      .booking-panel {
        flex-direction: column;
        gap: 1.8rem;
      }
      .seat {
        width: 28px;
        height: 28px;
        font-size: 0.6rem;
      }
      .seat-row {
        gap: 6px;
      }
      .action-bar {
        flex-direction: column;
        align-items: stretch;
      }
      .book-btn {
        justify-content: center;
      }
      .logo h1 {
        font-size: 1.5rem;
      }
    }
  </style>
</head>
<body>

<div class="booking-container">
  <!-- Header -->
  <div class="header">
    <div class="logo">
      <i class="fas fa-film"></i>
      <h1>Cine<span>Vibe</span></h1>
    </div>
    <div class="city-selector">
      <i class="fas fa-map-pin"></i>
      <span>Mumbai</span>
      <i class="fas fa-chevron-down" style="font-size: 0.7rem;"></i>
    </div>
  </div>

  <!-- Movie selection -->
  <div class="movies-grid" id="movieGrid">
    <!-- Movie 1 -->
    <div class="movie-card active" data-movie="Inception" data-price="350">
      <div class="movie-poster">🎬</div>
      <div class="movie-info">
        <h3>Inception</h3>
        <div class="movie-meta">
          <span><i class="fas fa-clock"></i> 2h 28m</span>
          <span><i class="fas fa-tag"></i> Sci-Fi</span>
        </div>
        <div class="rating"><i class="fas fa-star"></i> 8.8 / 10</div>
      </div>
    </div>
    <!-- Movie 2 -->
    <div class="movie-card" data-movie="Dune: Part Two" data-price="400">
      <div class="movie-poster">🏜️</div>
      <div class="movie-info">
        <h3>Dune: Part Two</h3>
        <div class="movie-meta">
          <span><i class="fas fa-clock"></i> 2h 46m</span>
          <span><i class="fas fa-tag"></i> Adventure</span>
        </div>
        <div class="rating"><i class="fas fa-star"></i> 8.6 / 10</div>
      </div>
    </div>
    <!-- Movie 3 -->
    <div class="movie-card" data-movie="Oppenheimer" data-price="380">
      <div class="movie-poster">⚛️</div>
      <div class="movie-info">
        <h3>Oppenheimer</h3>
        <div class="movie-meta">
          <span><i class="fas fa-clock"></i> 3h 0m</span>
          <span><i class="fas fa-tag"></i> Biography</span>
        </div>
        <div class="rating"><i class="fas fa-star"></i> 8.9 / 10</div>
      </div>
    </div>
  </div>

  <!-- Booking panel: showtimes & seats -->
  <div class="booking-panel">
    <!-- Showtimes -->
    <div class="showtime-section">
      <div class="section-label"><i class="fas fa-clock"></i> Select showtime</div>
      <div class="time-slots" id="timeSlots">
        <div class="time-btn selected" data-time="10:30 AM"><i class="far fa-sun"></i> 10:30 AM</div>
        <div class="time-btn" data-time="1:45 PM"><i class="fas fa-cloud-sun"></i> 1:45 PM</div>
        <div class="time-btn" data-time="5:20 PM"><i class="fas fa-cloud-moon"></i> 5:20 PM</div>
        <div class="time-btn" data-time="9:00 PM"><i class="fas fa-moon"></i> 9:00 PM</div>
      </div>
    </div>

    <!-- Seat selection -->
    <div class="seats-section">
      <div class="screen-indicator">
        <span>SCREEN</span>
        <div class="screen-curve"></div>
      </div>
      <div class="seat-grid" id="seatGrid">
        <!-- Rows A-D generated in JS -->
      </div>
      <div class="legend">
        <div class="legend-item"><div class="legend-box available"></div> Available</div>
        <div class="legend-item"><div class="legend-box selected"></div> Selected</div>
        <div class="legend-item"><div class="legend-box occupied"></div> Occupied</div>
      </div>
    </div>
  </div>

  <!-- Action bar -->
  <div class="action-bar">
    <div class="total-price">
      <div class="label">Total amount</div>
      <div class="amount" id="totalAmount">₹0 <small>INR</small></div>
    </div>
    <button class="book-btn" id="bookBtn" disabled>
      <i class="fas fa-ticket-alt"></i> Proceed to Book
    </button>
  </div>
</div>

<!-- toast message -->
<div class="toast" id="toast">
  <i class="fas fa-check-circle"></i>
  <span id="toastMessage">Booking confirmed! 🎉</span>
</div>

<script>
  (function() {
    // ---------- STATE ----------
    let selectedMovie = 'Inception';
    let selectedPrice = 350;
    let selectedTime = '10:30 AM';
    let selectedSeats = new Set();      // holds seat ids like "A1"

    // Occupied seats (static for demo, feel free to adjust)
    const occupiedSeats = new Set([
      'A3', 'A4', 'B2', 'B5', 'C1', 'C7', 'D4', 'D6'
    ]);

    // Seat rows config (A-D, 8 seats per row)
    const rows = ['A', 'B', 'C', 'D'];
    const seatsPerRow = 8;

    // DOM elements
    const movieCards = document.querySelectorAll('.movie-card');
    const timeBtns = document.querySelectorAll('.time-btn');
    const seatGrid = document.getElementById('seatGrid');
    const totalAmount = document.getElementById('totalAmount');
    const bookBtn = document.getElementById('bookBtn');
    const toast = document.getElementById('toast');
    const toastMessage = document.getElementById('toastMessage');

    // ---------- RENDER SEATS ----------
    function renderSeats() {
      seatGrid.innerHTML = '';
      rows.forEach(row => {
        const rowDiv = document.createElement('div');
        rowDiv.className = 'seat-row';
        for (let i = 1; i <= seatsPerRow; i++) {
          const seatId = `${row}${i}`;
          const seat = document.createElement('div');
          seat.className = 'seat';
          seat.dataset.seatId = seatId;
          seat.textContent = seatId;
          
          if (occupiedSeats.has(seatId)) {
            seat.classList.add('occupied');
          }
          
          if (selectedSeats.has(seatId)) {
            seat.classList.add('selected');
          }

          seat.addEventListener('click', (e) => {
            e.stopPropagation();
            if (seat.classList.contains('occupied')) return;
            
            // toggle selection
            if (selectedSeats.has(seatId)) {
              selectedSeats.delete(seatId);
              seat.classList.remove('selected');
            } else {
              selectedSeats.add(seatId);
              seat.classList.add('selected');
            }
            updateTotalAndButton();
          });

          rowDiv.appendChild(seat);
        }
        seatGrid.appendChild(rowDiv);
      });
    }

    // ---------- UPDATE TOTAL & BOOK BUTTON ----------
    function updateTotalAndButton() {
      const count = selectedSeats.size;
      const total = count * selectedPrice;
      totalAmount.innerHTML = `₹${total} <small>INR</small>`;
      
      if (count > 0) {
        bookBtn.disabled = false;
      } else {
        bookBtn.disabled = true;
      }
    }

    // ---------- SHOW TOAST ----------
    function showToast(message, isSuccess = true) {
      toastMessage.textContent = message;
      toast.style.borderLeftColor = isSuccess ? '#f5c518' : '#f87171';
      toast.querySelector('i').className = isSuccess ? 'fas fa-check-circle' : 'fas fa-exclamation-circle';
      if (!isSuccess) toast.querySelector('i').style.color = '#f87171';
      else toast.querySelector('i').style.color = '#f5c518';
      
      toast.classList.add('show');
      setTimeout(() => {
        toast.classList.remove('show');
      }, 2600);
    }

    // ---------- RESET SEATS (keep occupied, clear selected) ----------
    function clearSelectedSeats() {
      selectedSeats.clear();
      document.querySelectorAll('.seat.selected').forEach(seat => {
        seat.classList.remove('selected');
      });
      updateTotalAndButton();
    }

    // ---------- UPDATE MOVIE AND PRICE ----------
    function setMovie(movieName, price) {
      selectedMovie = movieName;
      selectedPrice = price;
      
      // update active movie card ui
      movieCards.forEach(card => {
        if (card.dataset.movie === movieName) {
          card.classList.add('active');
        } else {
          card.classList.remove('active');
        }
      });

      // when movie changes, clear seat selection (fresh start)
      clearSelectedSeats();
      // also reset time? Not mandatory but we keep the same time for UX.
      // update total amount (price changed but zero seats -> show 0)
      updateTotalAndButton();
    }

    // ---------- SET TIME ----------
    function setShowtime(time) {
      selectedTime = time;
      timeBtns.forEach(btn => {
        if (btn.dataset.time === time) {
          btn.classList.add('selected');
        } else {
          btn.classList.remove('selected');
        }
      });
    }

    // ---------- EVENT LISTENERS ----------
    // movie cards
    movieCards.forEach(card => {
      card.addEventListener('click', () => {
        const movie = card.dataset.movie;
        const price = parseInt(card.dataset.price, 10);
        setMovie(movie, price);
      });
    });

    // time buttons
    timeBtns.forEach(btn => {
      btn.addEventListener('click', () => {
        setShowtime(btn.dataset.time);
      });
    });

    // book button
    bookBtn.addEventListener('click', () => {
      if (selectedSeats.size === 0) {
        showToast('Please select at least one seat', false);
        return;
      }
      
      const seatList = Array.from(selectedSeats).sort().join(', ');
      const total = selectedSeats.size * selectedPrice;
      
      // Simulate booking success
      showToast(`✅ Booked ${selectedSeats.size} seat(s) for ${selectedMovie} (${selectedTime}) • Total ₹${total}`, true);
      
      // Mark selected seats as occupied (they're booked now)
      selectedSeats.forEach(seatId => {
        occupiedSeats.add(seatId);
      });
      
      // Clear selection and re-render seats (so they become occupied)
      clearSelectedSeats(); // this also clears set and UI selected
      renderSeats();        // re-render to show newly occupied seats
      
      // update button/total again
      updateTotalAndButton();
      
      // You could also disable time etc. but keep simple.
    });

    // ---------- INITIAL SETUP ----------
    function init() {
      // set default movie (Inception: 350)
      setMovie('Inception', 350);
      
      // set default time (already selected in html but ensure class)
      setShowtime('10:30 AM');
      
      // render seats with occupied map
      renderSeats();
      
      // set total to 0 and button disabled
      updateTotalAndButton();
    }

    init();
  })();
</script>
</body>
</html>
