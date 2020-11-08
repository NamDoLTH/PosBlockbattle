package blockbattle

case class Pos(x: Int, y: Int) {
  def moved(delta: (Int, Int)): Pos = new Pos(x + delta._1,y + delta._2)
}
