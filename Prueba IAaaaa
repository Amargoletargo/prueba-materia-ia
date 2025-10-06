import streamlit as st
from typing import List, Dict

st.set_page_config(page_title="Quiz de opción múltiple", layout="centered")

# --- Datos: 10 preguntas (texto, opciones, respuesta correcta, justificación, categoría) ---
QUESTIONS: List[Dict] = [
    {
        "id": 1,
        "category": "Ciencias Naturales",
        "question": "¿Cuál de los siguientes órganos se encarga de bombear la sangre en el cuerpo humano?",
        "options": {"a": "Pulmones", "b": "Hígado", "c": "Corazón", "d": "Riñones"},
        "correct": "c",
        "justification": "El corazón actúa como una bomba muscular que impulsa la sangre a través de los vasos sanguíneos, asegurando el transporte de oxígeno y nutrientes a todo el cuerpo."
    },
    {
        "id": 2,
        "category": "Geografía",
        "question": "¿Cuál es el río más largo del mundo?",
        "options": {"a": "Nilo", "b": "Amazonas", "c": "Yangtsé", "d": "Misisipi"},
        "correct": "a",
        "justification": "Aunque existe debate con el Amazonas, las mediciones más aceptadas indican que el Nilo es ligeramente más largo (~6,650 km)."
    },
    {
        "id": 3,
        "category": "Historia",
        "question": "¿En qué año comenzó la Segunda Guerra Mundial?",
        "options": {"a": "1914", "b": "1939", "c": "1945", "d": "1929"},
        "correct": "b",
        "justification": "La Segunda Guerra Mundial inició el 1 de septiembre de 1939 con la invasión de Alemania a Polonia."
    },
    {
        "id": 4,
        "category": "Matemáticas",
        "question": "¿Cuál es el resultado de 3^3 + 2^3?",
        "options": {"a": "25", "b": "35", "c": "30", "d": "33"},
        "correct": "b",
        "justification": "3^3 = 27 y 2^3 = 8; sumando ambos se obtiene 27 + 8 = 35."
    },
    {
        "id": 5,
        "category": "Literatura",
        "question": "¿Quién escribió Cien años de soledad?",
        "options": {"a": "Mario Vargas Llosa", "b": "Julio Cortázar", "c": "Gabriel García Márquez", "d": "Carlos Fuentes"},
        "correct": "c",
        "justification": "Gabriel García Márquez, escritor colombiano, publicó esta obra en 1967 y es un emblema del realismo mágico."
    },
    {
        "id": 6,
        "category": "Biología",
        "question": "¿Qué molécula contiene la información genética de los seres vivos?",
        "options": {"a": "ARN", "b": "ADN", "c": "Proteína", "d": "Enzima"},
        "correct": "b",
        "justification": "El ADN (ácido desoxirribonucleico) almacena la información genética necesaria para el desarrollo y funcionamiento de los organismos."
    },
    {
        "id": 7,
        "category": "Tecnología",
        "question
