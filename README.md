<div className="posterImage">
                <img src={movie.image} alt={movie.title} />
                </div>
                <div className="posterImage__overlay">
                  <div className="posterImage__title">
                    {movie ? movie.title : ""}
                  </div>
                  <div className="posterImage__runtime">
                    {movie ? movie.year : ""}
                    <span className="posterImage__rating">
                      {movie ? movie.rating : ""}
                      <i className="fas fa-star" />{" "}
                    </span>
                  </div>
                  <div className="posterImage__description">
                    {movie ? movie.description : ""}
                  </div>
                </div>
